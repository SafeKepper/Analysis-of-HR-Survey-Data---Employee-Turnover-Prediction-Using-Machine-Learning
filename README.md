
# Analysis of HR Survey Data - Employee Turnover Prediction Using Machine Learning

## Project Overview

The goal of this project was to create a classification Model and
conlude on a best performing Machine Learning Model (DecisionTree, RandomForest, Xgboost) to predict employee Turnover Left or Stay. The project utilised Salifort Motors HR
Survey Data. The final XGBoost Model performed with 94.5% F1, 97.1% Precision and 92.1% Recall determining what features were most important in seggregating Left and Stayed. Based on the modeling the main contributing factors were Tenure duration, High work hours, Satisfaction level, Total Project Contribution.


### Business Understanding 

According to International Labour Organisation the adopted Conventional work hours are 48 hours a week, This is significantly lower than the work hours in gathered data, It's important to Understand what factors encourage employees to work long hours and burnout leading to turnover.


### Data Understanding 

The Salifort Motors HR Data came from [Kaggle.com](https://www.kaggle.com/datasets/mfaisalqureshi/hr-analytics-and-job-prediction?select=HR_comma_sep.csv). The data consisted of approximately 15K Unique employees and 1- features. The features Included information from Tenure Duration, Satisfaction Level, Project Contribution, Last Evaluation, Salary, Department etc.

![Data Distribution](.//images/Split_turnover.png)


### Modeling and Evaluation 

Various Models were built, Concluded on a XGBoost model comprising 500 Desision trees was used to determine feature importance in will a employee quit or not. The below plot shows that Tenure duration, Satisfaction level, project contribution  are the top 3 most important factors and Monthly work hours are correlated to theses features.
The overall model performed with 98.1% accuracy and 94.5 F1.

![Important Features](.//images/output.png)


## Conclusion

The Model can benefit company in knowing if an employee will quit or not. Further examinations can be performed to look  t various phenomenon, at various tenure years. Focusing on Satisfaction level and various factors that contributing to that will be beneficial in helping the stakeholder address thier business problem retaining employees.
