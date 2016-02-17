#Kaggle: West Nile Virus Prediction#

##Predict West Nile virus in mosquitos across the city of Chicago##
https://www.kaggle.com/c/predict-west-nile-virus

####1. What is the problem you want to solve####
Predict the probability of the occurence of west nile virus in 
Chicago City at different locations. 


####2. Who is your client and why do they care about this problem?####
In other words, what will your client DO or DECIDE based on your analysis that they wouldn’t have otherwise?
Chicago department of publich health will be intertesed in the analysis. 
The prediction will help the department to efficiently allocate their 
resourses to the locations with the highest probability  of virus eruption. 


####3. What data are you going to use for this? How will you acquire this data?####
First part of data comes from Kaggle website:
 (1). Main dataset
 (2). Spray data
 (3). Weather Data 2007 to 2014
 (4). Map data for visualization
Second part of data comes from Twitter:
For example, the number of times people mentioned nail virus in their posts.

####4. In brief, outline your approach to solving this problem (knowing that this might change later).####
* Use statisical analysis and unsupervised clustering to do exploring analysis to detect the popential patterns in features
* Use supervised learning such as random forest, support vector machine to build predictiv model. Compare the performance
between different models and figure out the most informative features. 


####5. What are your deliverables? Typically, this would include code, along with a paper and/or a slide deck.####
The deliverables are composed of three/four  parts:
 1. Github repository stores codes for analysis
 2. A write up describes analysis process, results and insights
 3. A slide deck
 4. A website shows real-time prediction based upon the analysis
