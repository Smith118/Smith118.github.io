## About Exploratory Data Analysis (EDA)
Exploratory data analysis (EDA) is used performm analysis and investigation on data sets, find and summarize key characteristics that can help transform and manipulate data and find trends, anomalies  set up hypothesis testing etc. EDA also helps in performing data cleaning prior to setting up models for prediction or forecasting. This blog gives a basic summary about performing EDA on datasets and can help ordinary person understand about concept of EDA in a simple format by answering some questions.

## Strategy to use for EDA
The first and commonly used strategy to start with EDA would be to **understand the type of data in the dataset -numeric /character , continuous , discrete or categorical etc**. This can be done by summarizing the data or going through some rows of data or by creating tables.

The Next step will be to find **any missing data** and investigate if the missing data is characteristic of dataset or not . For example, in a sample survey missing rows do carry some information.

**Outlier Detection** is another important requirement that needs to be checked for numerical datasets. This is followed by **finding shapes, patterns and trends inside the data** . Next step is to **find correlations or relationship** between different variables and select them based on the goals set up for the analysis. For example for running a linear regression, EDA helps in selecting the regressor variables that best describe or show a strong correlate to the response variable.

## Overall Goal when doing EDA
The overall goal of the EDA is to **understand data and its underlying structure and extract all of the specific items that is needed to be extracted from a data set, such correlation, good ness of fit etc** . This in turn eases in selecting the methods that can be applied to perform a particuar analysis. For example a strong linear relation between two regressior and response variable will help analyst perform a simple linear regression instead of doing some complex algorithm based forecasting, and also save time and cost of doing analysis.

## Methods that could be important
Methods that can be important and generally accepted in all fields would be summarizing data.
1) Capturing basic statistics like mean, standard deviation, or features like min, max etc.
2) Making contingency tables or pivot tables.
3) Using graphs like- bar plot or histograms Box Plots, Heat Maps Scatter plot (for correlations), Line Plots (time series) etc.
4) Dimensionaliy reduction or scaling of data (for more complex datasets) 

## What are the things to look for.

The Most important aspects would be to figure out are: 

1) Type of data in the dataset,
2) Find missing values ad their importance
3) Categorize Values
4) Find shape of dataset 
5) Identify all relationships 
6 )Find anomalies / outliers 
7) Make assumptions or hypothesis before building the model.

EDA helps im core understanding of different variables by extracting different pieces of information, iikes, mean, variance, etc.
It can identify any major discrepancy, anomalies, or missing values in their dataset, which is very important before any comprehensive analysis and can help se the Using data visualisations and tables it can help analysts choose and use tools available to them more effectively, get key insights and make conclusions. 
