# Case Study 02 - Employee Attrition for DDSAnalytics

YouTube Presentation: https://www.youtube.com/watch?v=3SXL037Iprc   
RShiny App:https://vochannguyen.shinyapps.io/VoShiny2/  

## Introduction and Purpose
DDSAnalytics company is specializing in talent management for Fortune 100 companies. We, as data scientists, are going leverage our talents and skill for their talent management department. The executive leadership has identified predicting employee turnover, and we will be creating a model to predict attrition. Additionally, we will be using a selection model to predict salary based on our predictor variables.

## Datasets
The Attrition dataset contains a list of 870 employees with 36 possible predictor variables. 

### CaseStudy2_data.csv:  
ID, Age, Attritrion, Business Travel, Daily Rate, Department, Sales, Research & Development, Human Resources, Distance From Home, Education,  Education Field, Marketing, Life Sciences, Medical, Technical Degree, Other, Employee Count, Employee Number
Environment Satisfaction, Gender, Hourly Rate, Job Involvement, Job Level, Job Role, Job Satisfaction, MaritalStatus, Monthly Rate, NumCompaniesWorked, Over18, overTime, PErcent SalaryHike, PErformance Rating, Relationship Satisfaction, Standard Hours, Stock Option Level, Total Working years, Training Times Last Year, Work Life Balance, Years at Company, Years in Current Role, Years since Last Promotion, Years with Current Manager

### Task #1 - Exploratory Analysis on Predictor Variables on Attrition
### Task #2 - Build Attrition Model using using Naive Bayes (Experimental on KNN)
### Task #3 - Build Salary Model using Multiple Linear Regression

## Table of Contents
1.Case Study 2 Data Set, Case Study Comp Datasets for No Attrition and Salary  
2. Prediction Dataset (CSV) for Attrition - Predicted Attrition is the last column  
3. Prediction Dataset (CSV) for Salary - Predicted Salary is last column  
4. Full Case Study 2 EDA & Analysis (.md, HTML)  
5. Vo Nguyen Case Study 2 Links for RShiny, YouTube Videos, My Website


## Conclusion  
Attrition Model: Naive Bayes
+ Naive Bayes with selected Predictors was better than the KNN model.
+ The Predictor Variables we use for Naives Makes Sense in how they were used in our Models to give us the best Accuracy, Sensitivity, and Specificity.
+ We might have some errors due to my own hand selection of models by putting on one variable at a time.
+ The best top three predictors of Attrition are JobLevel, Monthly Income, and Overtime

Salary Model: Multiple Linear Regression
+ Multiple Linear Regression using the selected Predictors from the interactions and overall regression provided statistical values that makes sense.
+ Interaction terms created powerful p-values we can use for our model.
+ The best level predictor of incomes are Job Level, Total Working Years, and Job Roles were our top three salary prediction predictors.
## Credit
Vo Nguyen
