## Finetuning
- Training the LLM on your own data for more specific domain/context
- Gets rid of hallucinations when the questions are based on some specific context that the LLM isnt trained on
- Prevents data leakage from third party options, no breaches
- updates all of the model weight not just parts of it but can use advance techniques to only update some parts of it-- maybe more text/tokenization prediction

## Pretraining
- almost zero data so has no knowledge of anything
- will scrape information from the internet as nothing to get the wods from and will make tokenize predictions
- a lot of these are not good at chat bot interface
- add more data in with fine0tuning to be able to create more chat bot style
- Use self-supervised unlabeled data and use labeled data to curate yourself--- this is ideal
- with LLM just the text-in and text-out-
	- **extraction**- text in, less text out: so more reading and using keywords- this is a not as complex task and doesnt require large models and larger data sets
	- **expansion**- text in, more text out: things like writing and chatting, coding- this is more complex task and needs larger models and larger training data sets
- **Steps for finetuning**-
	1. Identify tasks by prompt engineering large LLM
	2. FInd tasks you see LLM doing ok at
	3. Pick a task
	4. Get 1000 inputs and outputs for the task (make sure does better than just the step 2)
	5. Finetune a small LLM on this data
- Can use question+answer type of string to be more specific with questions to give a specific answer baclk

## Instruction Finetuning
- Teaches the LLM to follow a model and behave like a chatbot (this turned GPT-3 into chatGPT-3)
- How to finetune the LLM
	- **Data Prep**- tailoring the data set to your type of information you want
		- Using higher quality data that is correct responses
		- Diverse data for different scanrios to reduce bias
		- Real data is very effective because its more real-case scenario rather than generated data that is more fake
		- More data is better than less data
		- Method to data prep:
			1. Collect intruction-response pairs (labeling data)
			2. Concatenate pairs- add prompt templates if possible
			3. Tokenize the data- turning the words/subsets/phrases into numbers (encoding- things like hot-word encoding)- tokenizer is associated for each model and is important to work with the model, can cause problems if using the wrong tokenizer with the wrong model
			4. Split into train/test (80/20 or 70/30)
	- **Training**- training the model on the data set
		- What it does is take in training data and calculate the loss, backprop through model and update weights
		- Create epochs (how many times the training goes over the data set)
		- Batch the data into sections
	- **Evaluation and Iteration**- Evaluating how well it does and changing things to imporove
		- **Human evaluation**- having experts in the domain evaluate the output for reliability
		- **Test Suites**- Having test data and make sure that the test data is high quality, accurate, generalized and not seen in training data
		- **Elo Rankings**- A-B test between models
		- There are different suite of evaluation methods that do different things which can be used for testing
		- **Error analysis**- categorising the erros so you can understand what errors are happening and why they are happening
			- This required training model beforehand to understand where errros can pop up- 
				- things like misspelling words in the training data
				- Too long examples
				- Repetitive data set examples
- **Practical steps to finetuning**-
	- important to vary the amount of data to give the model as different amounts may have a different impact on the performance of it
	- IMportant to evaluate the model as well to see if working or not 