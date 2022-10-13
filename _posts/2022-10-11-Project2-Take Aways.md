# Project 2 Takeaways

## Purpose of Project
The Project 2 is about creating a vignette about contacting an API query, parse, and return well-structured data using functions. Handle APIs and fetch data from them using R. Understanding the data and converting them to presentable tables or dataframe and performing exploratoty data analysis.

The working and results of the project can be seen in the following links.

Link to the rendered github repo
[Link to the Vignette](https://cassioaumonti.github.io/project2T/)

Link to the regular repo
[Non-github pages site](https://github.com/cassioaumonti/project2T)

## About working on the project

### Contribution to the Project and Interesting Findings.

My honest take on this is that my commits are not as many as my partner because I have mostly made my commits all together after completing all bulk changes, or additions and updating my sections. I have ensured that I have covered all the learning outcomes and requirements for this project. 

With given information and project scope, I decided to use technical endpoints of API to showcase pattern that helps investors in buying and selling of securities. Although the data limit is very less in this case but it can still show a glimpse of comparison between trends of various securities in the pool. I looked at all technical indicators endpoints at my end and decided to go for the Moving Average Convergence/Divergence (MACD) as an **additional API** (test API in my commits) to the code as part of my contribution and went on to prepare data for it. 

I also got a chance to work on the **Exploratory Data Analysis** from which I did the renaming of variables (eventually absorbed in a function), summary tables, an addtional variable like "cumulative typical price" and some plots out of which some good ones were used for final. My partner mostly handled the document and its final version and made some structural coding changes in my contribution of plots, codes and texts.

The polygon.io contains a rich amount of data on stocks for different time intervals. The Grouped Bars endpoint provide the historical log of the price, transactions and trading parameters for one company. Aggregate bar endpoint similarly, gives long term historical log of trading activities, but the information bears more importance for analysts when it is used with technical indicators that help identifying pricing trends and use them to forecast the future price!. So parameters like moving averages , Moving Average Convergence/Divergence (MACD) etc are very important for analysing the market and performance of different stocks/securties and identify opportunities to develop algorithms and solutions for handling inflation and other market affecting events. It was interesting to see signal lines and MACD lines give so much information for a short span.

### Process I went through for this project.
Mostly I have worked from night to early morning project as I do for rest of my coursework and homeworks, just like most of my peers do in the coursework. My initial excercise included understand the data first and see scope of EDA that can be done before finalizing the dataset. I did do some prior work on EDA first for all datasets as to test what EDA is possible with what data. This polygon set and beer data were the first best choice for me.  

### Most difficult part of the logic and programming ?
I understood the scope and initial work done on the project. Then in next step, I went on to explore options where I could fit my ideas into the structure of the project and the work being done by my partner. I had worked on fetching the API before and also helped my partner figuring how to get the data from this so , understanding the working of API was not complicated part. The only part that consumed time was to go though the preliminary work already done in the R code, understand frequent changes in code every day and merge my work into that. I had also taken up to do some EDA  but I did not expect that sometimes layering in ggplot2 can cause a lot of mess. I found ggplot2 is avery sensitive function so some lines threw lot of error and took a lot of time to resolve those. It does have some rules and we need to be particular about them to avoid error and warnings. The other challenge was the cap in the usage of the key. I had to make **third API key** from my personal email as two were not sufficient for these many queries.

### What I woud do differently in approaching a similar project in the future?

My idea about the project was to take long term data for one or two companies and work out on their historical trends using aggregate endpoint and 2 technical endpoints. And use some EDA on this to find the key performance points that can help select useful parameters for use into a time series forecasting model. I have some inclination towards time series data and this is the one of the main purposes, that these many bulk data are created and accessed through APIs as it helps analysts identify trends, work on developing strategies and even do forecasts. It would be a good initial excercise to get aquainted with the data first and perform some basic reporting on observations.
