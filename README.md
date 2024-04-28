
# Analysis of HR Survey Data - Employee Turnover Prediction Using Machine Learning

## Project Overview

The goal of this project was to create an ML classification Model and
conclude on a best performing Machine Learning Model (DecisionTree, RandomForest, Xgboost) to predict employee Turnover Left or Stay. The project utilised Salifort Motors HR survey data. The final XGBoost Model performed with 94.5% f1 score, 97.1% precision score and 92.1% recall score determining what features were most important in segregating employees who left and stayed in the company based on the model, the main contributing factors were Tenure duration, High work hours, Satisfaction level, Total Project Contribution.


### Business Understanding 

According to the International Labour Organisation, the adopted conventional work hours are 48 hours a week, This is significantly lower than the work hours in the gathered data, It's important to understand what factors encourage employees to work long hours and burnout, leading to turnover.


### Data Understanding 

The Salifort Motors HR Data came from [Kaggle.com](https://www.kaggle.com/datasets/mfaisalqureshi/hr-analytics-and-job-prediction?select=HR_comma_sep.csv). The data consisted of approximately 15K Unique employees and 1- features. The features Included information from Tenure Duration, Satisfaction Level, Project Contribution, Last Evaluation, Salary, Department etc.

![Data Distribution](.//images/Split_turnover.png)


### Modeling and Evaluation 

Various models were built, Concluded on a XGBoost model comprising 500 Desision trees was used to determine feature importance in deciding whether an employee would quit or not. The below plot shows that tenure duration, satisfaction level, and project contribution  are the top 3 most important factors, and monthly work hours are correlated to these features.


![Important Features](.//images/output.png)
Overall, the model performed with 98.1% accuracy and 94.5% F1.

## Conclusion

The model can benefit the company by letting it know if an employee will quit or not. We can conduct further examinations to investigate various phenomena that occur at different tenure durations. Focusing on satisfaction levels and various factors that contribute to that will be beneficial in helping the stakeholder address their business problem of retaining employees.
