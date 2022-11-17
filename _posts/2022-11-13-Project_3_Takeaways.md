# Project 3 Takeaways

## Purpose of Project
The Project 3 is about using OnlineNewsPopularity dataset to perform some Exploratory Data Analysis and apply machine learning models , specifically Linear Regression models and Ensemble models to predict the respons variable called **shares**. The dataset has been split into 6 different categories of datasets based on a categorical variable **data_channel_xx** . The analysis and predictions on these 6 sets of data has been automated using R code and a single .Rmd file was fed with all these datasets and results was taken out as 6 separate github document.

The link to the files is given below:

Link to the rendered github repo:
[Link to the Projectfiles](https://pmb-7684.github.io/ST558_Project_3/)

Link to the regular repo:
[Non-github pages site](https://github.com/pmb-7684/ST558_Project_3)

## what can be done differently?

OnlineNewsPopularity is a wide dataset and I by all means prefer to try what is minimal for me cost wise and labour wise. I would definitely approach this problem first with some basic EDA that is to get my variables and see their datatypes, some bulk scatter plots using `ggpairs()` like I applied in the code. The next step would be to study the plots carefully which I may have not done so much. I would prefer looking at those in detail with some good amount of time spent into it. I would go with PCA first just for EDA and see what it says, It is apparent that these many variables definitely may have some collinearity. So yes, PCA works out. So scatter and PCA can give me some answers. In a different aspect to give a try in reducing dimension and enhancing relation, I might prefer reshaping some columns into categories and use a category over them. Forexample, I can create a categorial variable called 'word' here and compare negative word counts with positve word counts , and see which one is greater and place a binary vairable of 0, for more negative words and a 1 for more positive counts. I am hoping this might help us reduce some corrrelation among many related variables like these. 

##  Most difficult part ?
 
Programming wise I did not see much hinderance , but yes the automation script was something I needed to preactice. As this was being covered already in the project by my partner,  I just did a backend practice at my end from the lecture examples again to get more clarity of the project instructions. I did do the running of the rendering of the code at my end during development to point out discrepancies in the code during the rendering and we worked on correcting those. So I am pretty comfortable with the rendering part now. I am happy that given my hectic schedule , I was able to do my sections on time and apply the methods I had intended on using.

### Big take-aways from this project?

OnlineNewsPopularity is one of the most critical data in every industry today. This dataset is based on careful collection of information from every field whether is is political, economic, tech, social media , entertainment etc. Thus, this vast dataset also of has broad set of variables that needs to be handles carefully given limited manpower, cost and resources. It does show how practical a data may look like and everything is not sugar in a dataset!!

To handle such data it is always to keep a clarity of concepts on EDA and machine learning models that we intend to use. Automating analysis on this type of data is very much advisable but this needs to be improved continuously till we get robust analysis and modelling. It is very good practice dataset for people looking to learn more on machine learning models. 
