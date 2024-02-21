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

### Analyzing Marital Status vs Income 
### The code for this anlysis is in data_cleaning.ipynb
 -The mean monthly income for married individuals (6793.67) is slightly higher than for divorced individuals (6786.29) and significantly higher than for single individuals (5889.47). However, the differences in mean income between marital status groups are relatively small. Median Monthly Income:

 -The median monthly income provides a measure of central tendency that is less affected by outliers. The median income for married individuals (5204.0) is higher than for divorced individuals (5131.0) and single individuals (4536.0). Standard Deviation
 
 -The standard deviation measures the variability or dispersion of income values within each marital status group. A higher standard deviation indicates greater variability in income within the group. The standard deviations for all three marital status groups are relatively close, indicating similar levels of income variability. Based on these observations, we can draw the following tentative conclusions:

- While there is a slight difference in mean and median incomes between marital status groups, it's not substantial enough to conclusively state that marriage significantly influences income. The variability in income within each marital status group is similar, suggesting that other factors besides marital status may have a stronger influence on income levels. Ultimately, drawing definitive conclusions about the influence of marriage on income would require more comprehensive analysis, considering additional factors and potentially employing statistical testing to assess the significance of any observed differences.


## References 
[Kaggle](https://www.kaggle.com/datasets/rishikeshkonapure/hr-analytics-prediction/data)
