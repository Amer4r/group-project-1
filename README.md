# group-project-1

## Overview

## Datase
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


### Exploring the Relationship Between Job Roles and Job Satisfaction

 - Understanding the intricate relationship between job roles and job satisfaction is crucial as it directly impacts the work environment and employee performance. This analysis delves into whether job roles influence job satisfaction, shedding light on the dynamics between these two critical factors.
 
#### The code for this analysis is in 'jobroles-vs-jobsatisfaction.ipynb' 

  - The analysis, conducted in the Jupyter Notebook file named "jobroles-vs-jobsatisfaction.ipynb," employs various visualization techniques, including pie charts, line charts, and bar graphs. By exploring these visualizations, we aim to uncover insights into the connection between job roles and job satisfaction.

  - Throughout the analysis, it becomes evident that job roles indeed play a significant role in determining job satisfaction levels. Bar graph provide a comprehensive overview of the distribution of job roles within the organization, while line charts showcase average trends in job satisfaction across different roles. Pie Charts offer a detailed comparison of job satisfaction levels across various job roles.


## References 
[Kaggle](https://www.kaggle.com/datasets/rishikeshkonapure/hr-analytics-prediction/data)