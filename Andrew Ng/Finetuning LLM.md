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
	- **extraction**- text in, less text out: so more reading and using keywords
	- **expansion**- text in, more text out: things like writing and chatting, coding
- **Steps for finetuning**-
	1. Identify tasks by prompt engineering large LLM
	2. FInd tasks you see LLM doing ok at
	3. Pick a task
	4. Get 1000 inputs and outputs for the task (make sure does better than just the step 2)
	5. Finetune a small LLM on this data
- Can use question+answer type of string to be more specific with questions to give a specific answer baclk