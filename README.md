# Udacity_Project1: A study of parameters influencing dissolved oxygen concentration in a stream waterbody in Florida

Please follow the link for the GitHub repository:
https://github.com/Liang-Environmental-Consultant/Udacity_Project1


Please follow the link for the blog post:
https://medium.com/@lilianli1986/a-study-of-parameters-influencing-dissolved-oxygen-concentration-in-a-stream-waterbody-in-florida-96f8038c170a

Introduction:
Dissolved oxygen in water is important and finding parameters influencing the dissolved oxygen (DO) concentration can establish a healthy aquatic community. Paramters may influence DO include salinity, water temperature, total nitrogen, total phosphorus, and chlorophyll-a. In this study, data including DO, salinity, water temperature, total nitrogen, total phosphorus, and chlorophyll-a from WBID 2189A were collected and the parameters affect dissolved oxygen were investigated through multiple linear regression model using Phython. 

Files included: 
Data file is named as: Data.xlsx.  
Python code is named as: Project 1.ipynb

Process included: 
1. Business understanding: What is DO? Why it's important to know the paramters influence DO in waterbodies? What parameters have great effects on DO in this waterbody? How do those parameters influence DO? Do the model results make sense? How to improve model performance to better interpret the relationship between DO and other parameters?
2. Data understanding: Data used to build the multiple linear regression model are collected from Florida Department of Environmental Protection website: https://floridadep.gov/dear/watershed-assessment-section/content/basin-411-0 Specifically, WBID 2189A data were extracted from Run 58 database. An ID column was added to the raw data file for the future data preparation. 
3. Preparing data: To get the clean data, missing values were replaced by the mean value. Categorical variables were excluded in the analysis. 
4. Data modeling: Multiple linear regression model was applied in this study. In this model, DO is the dependent parameter, while salinity, water temperature, TN, TP and chlorophyll-a are independent parameters.
5. Evaluate the results: R squared, Predicted VS Actual DO data plot and parameter coefficient were evaluated to answer questions asked above. 

Conclusion: 
This study suggests salinity, total nitrogen and total phosphrus have a great effect on dissolved oxygen in WBID 2189A. To improve model performance, more data need to be collected and other non-linear model such as regression tree needs to be considered. 
