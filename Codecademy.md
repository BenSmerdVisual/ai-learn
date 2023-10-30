# Fundamentals of AI/ML
## Data Literacy
- **Garbage in, garbage out**- answers to data can be only as good as the data that its working on- a lot of data is misrepresented by the analysis of it- is there enough sufficient data and can we get an exact answer to the question from this data
- **Participation Bias**- if the data is not fully refelctive of what the question is then the bias can take effect and not provide the full result to whatever the question is 
- **Variables** - when measuring variables in a specific scenario- **numberical** variables are measured and **categorical** are categorized
	- **Numerical**- Combination of the measurement and the uni-- need what you are measuring and how many of it is the measurement
	- **Categorical**- Describe characteristics with words or relative values
		- **Nominal**- A named value
		- **Dichotomous**- only 2 logical possiblities (yes/no)
		- **Ordinal**- some sort of scale where there are multiple possibilties of choice
- Important to look out for any **missing data** as this can impact the results that you're looking for within the data set, it's not completely necessary to remove it but as long as it's taken into account when making the analysis of it
- **Accuracy**- need to make sure the dataset that you are using to train the model accurately describes the world
	- **Standardization**- having a set guidleines that the data collecting must adhere by to ensure that the data isn't inconsistent with other data
	- IMportant to think critically about the data and spot any common sense inaccuracies that may be a reason for outliers. Think about how any error could have crept in during the data collection process and this can uncover systematic inconsistencies. Identifying possible ways that duplicate data could have been created
- **Validity**- Making sure that the data actually measures what is set out to measure
	- Understanding that the specific variables used to make the measurements of the data actually reflect the answer that you are trying to find
- **Sample representation**- cant test everything, so having a diverse sample size which can be representative of the most key features of the data needs to be used 
## Statistical Thinking
- **Summary statistics**- Measuring and summarising the variables in a dataset
- **Categorical Thinking**- Storing qualitative variables into categories that can tell us more about it when we dont have numbers to
	- **frequency**- the count of how many times a certain variable is there (guitarist= 3, pianits=2, vocal=8)
	- **proportion**- the frequency divided by the total number of that category- total = 3+2+8=13 (guitarist = 3 / 13, pianist=2/13, vocal=8/13)
	- **percentage**- proportion converted from decimal to percent- proportion X 100
- **Distribution**- funcionality that shows how frequently each value occurs within all possible values of that variable
	- **Normal distribution**- typicall known as the bell-curve where an average will be in the middle indicated by larger frequency of that value occuring compared to the lower/higher ends where there's less values occuring
	- TO find more explicit results, use **mean** (average) and **standard deviation** (the spread of results)
	- **SKewed distribution**- having the graph being asymmetrical where one side has more frequency than the other- if more on right it is positively skewed and left is negative skewed (when the tail is on that side)