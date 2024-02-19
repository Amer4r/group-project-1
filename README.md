# group-project-1

## Overview

## Dataset
### Dataset was taken from the following website:
- Kaggle

### The dataset contains the following 29 columns:
- Age
- Attrition
- BusinessTravel
- DailyRate
- Department
- DistanceFromHome
- Education
- EducationField
- EmployeeCount
- EmployeeNumber
- EnvironmentSatisfaction
- Gender
- HourlyRate
- JobInvolvement
- JobLevel
- JobRole
- JobSatisfaction
- MaritalStatus
- MonthlyIncome
- MonthlyRate
- NumCompaniesWorked
- Over18
- OverTime
- PercentSalaryHike
- PerformanceRating
- RelationshipSatisfactio
- StandardHours
- StockOptionLevel
- TotalWorkingYears
- TrainingTimesLastYear
- WorkLifeBalance
- YearsAtCompany     
- YearsInCurrentRole 
- YearsSinceLastPromotion
- YearsWithCurrManager

## Data Cleaning
Data cleaning can be found on the 'data_cleaning.ipynb' file. 
Data cleaning process included the following steps:
- Reading the file
- Check for missing data (in this case we don't any missing data)
- Dropping unuseful data ('BusinessTravel', 'EmployeeCount', 'DistanceFromHome', 'Over18', 'StockOptionLevel', 'StandardHours')
- Getting the mean, median, var, std, sem for each column for our dataset

## Analysis

### Monthly Income and Attrition
In this comprehensive analysis, we delve into the intricate relationship between monthly income, employee attrition, and job satisfaction within the organizational landscape. Our primary objective is to discern whether monthly income serves as a pivotal factor motivating employees to seek greener pastures elsewhere, and to ascertain its potential influence on overall job satisfaction levels.

#### The code for this analysis is in 'monthly_income_and_attrition.ipynb' 

- Income Disparities Across Departments: Our analysis reveals significant discrepancies in monthly income between employees who choose to leave and those who remain within each department. These disparities highlight potential areas for further investigation into the factors influencing attrition rates within different organizational units.

- Impact of Income on Job Satisfaction: Interestingly, our findings suggest that while income plays a crucial role in employees' decisions to leave, it does not appear to have a substantial impact on overall job satisfaction levels. This nuanced relationship underscores the complexity of factors influencing employee attitudes and underscores the need for a holistic approach to workforce management.

- Relationship Between Income and Employee Attrition: The correlation between monthly income and employee attrition rates is striking. Our analysis indicates a pronounced spike in attrition among individuals earning lower incomes, with a notable decrease in attrition rates as income levels rise. This underscores the pivotal role of income in influencing employee retention strategies and highlights the importance of equitable compensation practices.


## References 
[Kaggle](https://www.kaggle.com/datasets/rishikeshkonapure/hr-analytics-prediction/data)