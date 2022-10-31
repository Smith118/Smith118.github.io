# Variable Selection in Regression Models

Why do we not use the data as it is to run pur prediction models? Why regression models needs data pre-processing? The answer to this question lies in the fact that we want to have the accurate information about the future. And the informaqtion is hidden in this real time data, from which we need to separate the usable information and get our predictions!. The information requires extraction by number of processes ad methods, and this varies by the type of data we are given. Data pre-processing is defined as process of manipulating or dropping of data before it is used in analysis or prediction to ensure authentic results and enhance performance. ghis requires process like Exploratory data Analysis , Transformation,  Feature Selection and Dimesnionality Reduction. Feature Selection and Dimensionality Reduction and dimensionality reduction are one of the most complex aspect of regression models as they determine the success of the regression model and the results for the prediction that we do with the regression fit on training dataset. Feature selection is selecting of the variables without transformaing them and using it as it is and Dimensionality reduction does the same thing with transformations on the data. What we will be discussing in this blog the Variable Selection or Feature Selection as it is first step in simplifying the data while getting the model fit. 

# Variable Selection Planning/Strategy

Prior to selecting variables for regression. The most important startegy is to understand the data Many variables can be selected through basic simple steps like - Through literature, experience about the data, or consulting through the experienced professionals in the related filed who are experts.

Other step includes understanding data ate our own end. This involves checks like -whether variables have outliers or they are skewed or they carry any relationship with each other etc.. This can be simply done by some initial steps like Exploratory Data Analysis using summary tables and graphs. Summary tables help understand data types here, and many unusable columns can be removed in this step. The box plot or histograms can show which columns skew and their intensity. Similarly, scatter plots help in identifying multi-collinearity between the columns or variables. Coreelated columns can be filtred out quickly from this step. 

Other aspect of planning includes identifying parameters that may be useful in selecting the variables. These can be p values, R Squared, OLS, RMSE, MSE etc.
The variable selection ethoods can then be selected and implemented and based on values of these matrics, the variables can be selcted. It is often a question what method might give optimal variables, this can be checked mostly with metric values and variables stated by these methods and use the ones which is recommended by most of the variable selection algorithms.

# Preferred Variable Selection Techniques.

1. **Scatter Plots / Correlation table or Heat Maps:**  To check relationship with response variable and Multi-collinearity among predictor variables.
2. **Box Plots/Histograms:** For checking requirement of any variable transformation. Skewness in dataset and outlier detection.

3. **Backward elimination:**
Backward elimination is the most simple variable selection meter in this the full model is used for regression and eliminated one by one until all remaining variables are considered to have some significant contribution to the outcome. The p statisitc is calcu;lated or each step here. This is a good method to start with variable selection as it tells the relationship of all variables with the response and during variable selection it removes the least significant variable first.

4. **Forward Selection:** It is reverse of the backward elimination method and starts with no variables in the model. At each step, each variable tested for inclusion  and  added to the model, the test statistic or p value is calculated. The variable with the largest test statistic is selected and added to the model. It is a good model where we want to use limited datasets and have computation limitations as the most significant variable is added first. 

5. **Best subset selection:** This estimates using all 2^p possible combination with predictiors, where is p is number of predictors. The best model is selected according crietria like AIC, BIC. For linear regression models, we want to minimize AIC or BIC. Larger models might get good fit but may use more parameters.AIC and BIC can be used as selection criteria for other types of regression models too not just for linear regression.

6. **Mallow’s Cp Statistic:** is close to Adjusted R2 and AIC and is easy to compute. So we can use this or Adjusted R2 and AIC together, for our our variable selection.

The other methods usable are RMSE /MSE that can help us as statistics for asseessing the variables that describbe the model but can be a length process as they require too many test runs. Criterian based methods like AIC, BIC, Cp R2 and Adjusted R2  etc can be helpful, but we need to careful about bias vs variance trade-off while working with our regression fit on training data and predictor variables.

