##  Project 1 : Takeaways
### Purpose of the Project1
The First Project was based on using R to read csv files, create functions to handle data and make plots in the output.
The purpose of the project was to implement learning outcomes on reading and manipulating data using various R packages and functionsto automate data handling reporting process. The various packages used here were tidyr, ggplot2,dplyr,tidyverse etc. The raw data to be used was log of enrollement for various schools in counties ,states  and overall counttry totals and first task contained making a function that reads csv file. Functions were created to do addtional taksks like reshaping the data from wide to long format using 'pivot_longer'. Select columns were extracted for further modification. Addtional columns like year and state were created by splitting existing columns using 'separate', 'substr' etc. Using 'grep'  The counties and non counties data were separated to get different datasets . The function calls contained reading multiple raw files of this raw format and combine them together. Plot functions were made as generic functions to get the plots fromthe statistic calculated from counties and non-counties data. The excercise helped in creating more detailed understanding on using packages and learn about good programming practices to be used while using these packages and making good reports. 

### Learning Outcomes from Project1
The key takesways from this project was to understand how to use functions and packages together to create general code templates for reports. This really helps to reduce repeated coding and save time. The project also helped in understanding syntax of various functions found in the packages in detail, while using them, for example substr can be used with mutate to get the select portions from the string and put them in a new column of the data frame. Or multiple outputs can be returned in function only by combining them into a list ot other object. This was perceived as a good practice to use R learning outcomes in detail and apply them to real world scenarios.

### Possible changes
The project could have been improved by tackling issues like maaintanin class type of the dataframes through out the projec.  A work around was introduced into the code to keep it consistent as in many cases functions returned multiple outputs. And this required bundling them into list. A good planning into the code could have helped in handling function returns better, given some additional time.

Link to the project.

[https://Smith118.github.io/Patnaik_Project_1_v2.html]





