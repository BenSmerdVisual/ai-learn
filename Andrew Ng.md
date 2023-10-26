# AI FOR EVERYONE
# Week 1- Introduction
- **ANI**- Artificial narrow intelligence- doing one guided version of AI- smart speaker, self-driving, web search, AI in farming and factories- have one trick about it- one specific task
- **AGI**- Artifical General Intelligence- build AI to do anything a human can do and do more than what a human can do
- More progress in ANI, rather than AGI as nowhere even close to the AGI, but very good progress on ANI 
- **What AI can/cant do today**- It can find basic examples when presented the examples, but it cannot figure out context of the examples--- this is the main problem
- **Machine Learning**- 
	- **Supervised Learning**- input to output mappings of information- if its someting basic and straight forward to input of an email and output of if its spam (spam filtering) or an english to chinese language translator- anything that you can do within 1 second though can be automated
		- Training larger amounts of data to be able to get better performance results
		- Using the labeled data so then the labels are recognised through the patterns by their results and then the label could be returned as the output as it is determined by the value that you are seeking- the supervision is having the kay being a supervisor of the value
			- **Regression model**- Predicting a continous-valued output like a housing price of a suburb or value of a speicif currency (as these values are constantly changing)
			- **Classification model**- Trying to predict a discrete number of values- like if something is a specific image based on a set of given images (cat, dog, tiger) or if something is something or is-not something (is this email spam)
- **Data**- Using the datasets to be able to recognise patterns within data of integers and being able to label specific data to maybe an image or some sort of visualisation- kind of a key:value tag
	- **Acquiring the data**- can either manually get it and add in relationships and keys to each piece of data- but this is too laborsome. Can observe behaviours and store the data and try make predictions based on previous behaviours. Can download from websiutes/partnerships etc. 
	- **Data problems**- data integrity and missing values can cause problems, need to data clean
- **Terminology**- 
	- **Machine Learning**- Learns the input to output- usually software running a algorithm of machine learning. Gives computers the ability to learn without being explicitly programmed (software)
	- **Data Science**- Analyse the data set to come up with the insight to improve businesses decisions. Extracting knowledge and insights from data (power slides)
	- **Deep Learning**- Using the neural networks to take in different sets of data and able to make an output based on each of the input, the neural networks basically checks for many different conditions to be able to provide the best slution- basically one complex and large mathetmatical equation
- **AI in a company**- Using strategic data acquisition and data warehouses to be able to store all their data and make decision based on it.
	- **AI  Transformation for a company**-
		1. Execute pilot projects to gain momentum
		2. Build an in-housr AI team
		3. Provide broad AI training
		4. Develop and AI strategy
		5. INternal and external communcation
- **Deep learning**- taking in all the factors that the person is using to try find the answer and being able to compare them to find the best answer, when comparing large scale data variables against each other to find the answer--- from the input its finding the best way to find the most efficient ouput
	- **neural networks**- are kind of like nodes tha have a specific value that can be combined from previous nodes and previous etc unbtil they find the value for the output

## Week 2: Building AI Projects
- **Machine learning workflow**- 
	1. Collect data- gather relevant information for whatever the task is- speech recognition would be people speaking the words relevant to what speech it is using
	2. Train model- Mapping the input data to start being able to produce output, usually the output would start off bad but it will gradually get better as the reinforcement of incorrect answers will start to correct the mapping to the correct answers
	3. Deploy model- Ship the model to users, starts getting new data that may not be used to what the trained data was on, need to maintain by updating the new data models types
- **Data science workflow**-
	1. Collect data- need to get the relevant information
	2. Analyze the data- need to recognise patterns to see what can change the business logic and practices to ehance the profit potential- iterate the ideas to get good insights
	3. Suggest hypotheses/actions- incorporating the actions to see what happens and re-analyze the new data impact on the business and re-integrate changes
- **Job function needs ML**- THe data scienbce will be used to optomize the manufactiuring line and the ML will automate the visual inspection of a product that could be being created in a manufactoring line. The data science can regonise the patterns of what needs to change because of the patterns and the ML will then use the data to determine the data that can be beneficial to the company and the data that isnt beneficial to the company
- **Choosing an AI project**- AI cant do everything to make your business better only some things
	- **Brainstorming**- automating tasks, not jobs- figure out the main drivers of the business value- what are the main pain points of the business (some can be slved by AI some not)- can make progress without the big data
	- **due diligence**- makle sure the technologt is good enbough to do what desired and how much data is needed to create it. Need to see if the business costs arent too high and if can create most efficiency and will the AI system actually increase revenue or help the business
	- **Build vs Buy**- dont have to build everything can buy things to make it so much easier and efficient
- When creating the workflow of data, usually have the training set which will be a set of data based on what you want the ML model to start analysing and then you will have a test set which will be different data models to test out and see how accurate the model can be when providing an asnwer to the question for it
- **Machine Learning Tools**- 
	- **Research publications**- Arxiv
	- **Frameworks**- Pytorch, TensorFlow, HugginFace

## Week 3- AI In Your Company
- Having a pipeline which handles the steps of AI being able to recognise intent from a question and be able to utilise the company data to be able to send back a response to the usert
	- Need to know the process for the command to be able to make most of each step
	- A lot of steps- things like being able to identify a certain word in the user input + recognising the intent of the word and what context it is being used in + being able to recognise if there was some sort of command eg "set a timer" and what sort of function this would then trigger
	- Understanding the steps of how the AI will work based on whatever the function that is causing triggers happens. the pipeline of what is happening based on input and ouput and key mappings
- **Roles in an AI team**- 
	- SWE- writing the execution code for the AI to be able to execute whatever the function is from the user input
	- Machine learning engineer- builing the software and algorithms for the machine learning so the ouput comes from the input
	- ML Researcher- Continue learning about ML and what are good practices/algorithms
	- APplied ML Scienties- Academic and literature to find the best practices and techniques of latest ML research
	- Data scientist- Examine the data and provide insights to better improve the business
	- Data engineer- ORganize the data and saved in an easy accessible and cost effective way
	- AI Product Manager- Help decide what to build, feasible and valuable
- **AI Transformation**- move into an AI company
	1. Execute pilot projects to gain momentum
		- More important for initial project to succeed rather than be value- choose something that has good chance of success
		- Make some traction within 6-12 months
		- First 1-2 projects can be in hour or outsorced
	2. Build inhouse AI team
		- Good to have a centralize AI team
		- Build company wide platforms/tools/infrastructure for the uni to work together
	3. provide AI training to most peoploe
		- Good to have most people that will be associated with the AI to understand what the AI can do and will do---- this relates to the workflow chart being able to get the consltants/sales to understand how it works
	4. Develop AI strategy
		- Leveraging AI to create advantage in our sector
		- Design strategy aligned with the Virtous Cycle of AI- better product = more users = more data = better product etc
		- Good at strategic data acquisition
		- Can collect data through free ways as this is a good way to collect data to enter the cycle
		- Building a unified data warehouse
		- create network effects and platfrm advantages- can accelorate so much
	5. develop internal/external communcations
		- Need to keep investor relations up to date to value the company appropriately
		- Need to keep up to date with government relations as its super important to work collaboratively to bring people the proper benefits
		- consumret user up to date
		- talent and recruiting and interal communications to bve able to keep up to date with what isw happening
- **AI Pitfalls**- Shouldnt rely on just few engineers- need to get people mixing up across the business
- **First steps in AI**- 
	- Join groups
	- Start brainstorming projects- can be even really small to see how it goes
- **Applicational areas of AI**- 
	- **COmputer vision**-  being able to take in a picture and classify it as a sepcific thing (eg cat, car, bike)
		- image classigication/object recognition-Process for the recognition needs a lot of register pictures and then take in new photos which then is a recognizing and comparing to the register pictures and using reinforcement if that new picture is the same classification as the register picture
		- Object detection- Doing the same bvut with objects, need a register object and then taking in the object recognition. This works differently to image classification as this will provide recognition if in the image there is an object within it
		- Image sementation- provides the pixel analysis if there are specific things within that image based on the pixel position
		- Tracking- detecting the movement and where specific movements happened before- its tracking the movements of something
	- **Natural language processing NLP**- understanding natural lanague for humans to communicate
		- Text classification- can detect if a specific bit of text is a key:value for what is being input- classifying the text into the key and return the value. Can also do sentiment recognition to see what type of sentiment a specific bit of text has, based on the language used
		- Information retrevela- stuff like web search, where you have a text query and the AI will return relevant information based on the context of the search query
		- Name entity recognition- Being able to recognise names within a sentence- peoples names, locations, organisations, countries. hpone numbers etc NER
		- Machine transalation- being able to translate words from languages
		- Parsing, part-of-speech tagging- Going through each sentence and being able to identify words based on if they are a noun, adjective etc and be able to structure the sentences based on linguistics. Parsing words as well to see how the words relate to one another
	- **Speech**- parsing audio data
		- Speech-to-text (speech recognition)- being able to determine what is being said from the adui waves
		- Trigger word/wakeword detection- being able to detect a specific word that can cause a trugger for a function (eg Alexa "Hey Alexa") and this can be in different langauges or with accents, needs to be accurate
		- Speaker ID- being able to identify the identtiy of the speaker, based on their voice
		- Speech synthesis(text to speech)- being able to have text to speech- someone writing text and then this can be turned into speech
	- **Robotics**- things like self driving car
		- Perception- figuring out things in the world around you like a human would with the senses- being able to detect specific things around you
		- Motion planning- being able to find a path for a robot to follow
		-  Control- sending commands to the motos to follow a specific path from a remote source
	- **General ML**- 
		- Unstructured data- being able to identify links between data that may be unstrcutreed. THis is usually random things like photos of cat recognition
		- structured data- mroe structure within the data- usually more specific to a singular company
- **Unsupervised Learning**- Doesnt tell the AI system what the answer is compared to supervised where you provide the AI the answer you are looking for- key mapping (the input must provide the output). Unsupervised finds meaningful things in the data based on what it can find as nothing is told to it to find. Can find things itself without having human input to look for something. 
	- **Clustering**- Tracking the data within different categories that are then clustered into smaller categories. Find patterns of data where there is data split into clusters that can provide two different lots of information. 
	- **Criticism**- it needs so much data to be able to identify things as it doesnt use label data (like supervised, where it is told what the object is) it is simply using the data that is being input to then be able to identify what the object is over time--- similar to a human that isnt told what an object is, it will identify it from its own experiences and interactions
	- **Future**- can provide a more humanistic approach to learning than just machine like
- **Transfer Learning**- Trasnfering the data from one set of rules into a nother set of rules (changing the data rules for car detection to truck detection)- Learn from task A (car) and use knowlege to help on Task B (truck). Because if you have a larger set from the Task A this can be massive help to detecting in Task B. Not very popular but can work in some areas
- **Reinforcement Learning**- Just the usual trial and error form of learning- make a mistake and then it will learn to not do that again, and then it will try to do actions which will be successful and help make the goal achieveable. Requires the reward signal to tell the AI if it is working or not working well- usually number based like a scale which would be coded in to be able to then adapt to it to maximise the rewards
	- weakness- requires huge amount of data and information, with things like games it can just play against itself to learn which isnt bad but then other forms of it in real life scenarios it requires huge amount of data
- **GANs Generative Adversial Network**- synthesize new images from scratch
	- Being able to create images based on text and the iamges out there- kind of like midjourney
- **KNoweldge Graph**- A database that will hold information about a specific topic- databases for companies and their own data based on the topic and knowledge for it (VC information about carers etc)

## Week 4- AI and Society
- **Realistic view of AI**- Cant be too optimistic and pessimistic
- **Biased AI through data**- biased data can result in biased AI
	- Learning through text on the internet can learn bad stereotypes
	- Good way to combat it is getting rid of any bias - "Zero out"- addng a zero to that data set to remove it
	- Good to be transparent with any bias present and have auditing
- **Adversarial attacks on AI**- Make the AI do something other than what it was intended to do- 
	- minor perurbation can happen through a slight change in the data- e.g. image recognition if there is any sort of pixel change in the data set
	- Things like changing physical appearance to trick AI systems- eg a man wore funky glasses which tricked the AI system into thinking it was a well known actress- putting stickers on a stop sign and it cannot detect the stop sign
	- **Adversial defences**- high cost to be able to combat this though- but also there is an arms race against it 
- **Adverse Users in AI**- Bad people in the space
	- Deepfakes- synthesize vidoes of people doing things that they never did- also can be sound
	- Undermining democracy and privacy- can be done through oppressive surveillance
- **AI Developing Economies**- 
	- Utilising AI to allow underdeveloped countries to leapfrog into a developing economy- things like mobile phones and where countries didnt use landlines, they skipped straight to mobile phones- India and China
	- Good for countries to utilise AI in areas that they are already good at- eg if they are good at exporting Wine then use AI to help export Wine
	- accelrate the public-private partnerships to accelerate development
- **AI and jobs**- automating jobs and many will be replaced and many will be created
	- Some companies thinks that AI will create more jobs than displace jobs
	- **Conditional basic income**- Not a UBI but having a safety net, but also incentivising people to learn
	- Lifelong learning society needs to be initiated because the learn for 4 years in college and cruise off that does not work
	- Learn AI and use it combination with the area you like

# Opportunities in AI
- **Sueprvised learning**- labeling the input so then you can know what the output as well, the output is labelled as well so it essentially has examples to be able to match the input to to determine the output 
	- More input data examples means better model performance
- **Generative AI**- 
	- **Text genereation eating**- Putting in a prompt and returning some sort of output related to the input- CHATGPT
	- 