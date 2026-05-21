# IBM HR Project
<img width="1241" height="330" alt="Gemini_Generated_Image_rmu8g7rmu8g7rmu8" src="https://github.com/user-attachments/assets/2bfd3198-be7a-425b-8f2e-e32fbf73b1fb" />



## This projects is all about finding the attrition pattern in the company.

## Introduction
* This is a attrition dataset record set of IBM. In this project the data is been used for finding the reason for attrition of the employees on the basis of the features in dataset.

## About Dataset
* The dataset contains corporate HR analytics detailing employee backgrounds, satisfaction metrics, performance evaluations, and tenure statistics for 1,470 employees across 35 features. There are no missing values across any of the attributes in the dataset. The primary goal of this data is to analyze employee turnover and build predictive models for employee retention using the target variable, Attrition.
* The dataset tracks employee information through demographic attributes including Age, Gender, MaritalStatus, and whether they are Over18. Organizational and operational contexts are defined by an individual EmployeeNumber, the specific Department, their assigned JobRole and hierarchical JobLevel, the frequency of BusinessTravel, the commute DistanceFromHome, and whether they work OverTime. Financial parameters are recorded through compensation metrics like MonthlyIncome, HourlyRate, DailyRate, and MonthlyRate, alongside performance incentives such as PercentSalaryHike and StockOptionLevel.
Workplace sentiment and background qualifications are captured via survey metrics including Education level, EducationField, EnvironmentSatisfaction, JobInvolvement, JobSatisfaction, RelationshipSatisfaction, WorkLifeBalance, and the latest PerformanceRating. Career history and tenure are monitored using NumCompaniesWorked, TotalWorkingYears, TrainingTimesLastYear, YearsAtCompany, YearsInCurrentRole, YearsSinceLastPromotion, and YearsWithCurrManager. Finally, the dataset includes internal operational constants like EmployeeCount and StandardHours, all centered around the main target variable measuring employee Attrition.

## Problem Statement 
* Find the attrition reason of IBM using the data provided.
* Build a model to identify if any employee is about to leave the organization.

## EDA(Elaborative Data Analysis) methods and results
* Univariate Analysis
Attrition (Target): Highly imbalanced; $83.88\%$ of employees stay while $16.12\%$ leave.Age: Near-normal distribution centered around a mean of $\approx 37$ years, with the majority aged between $30$ and $43$.Department: Heavily skewed toward technical roles—$65.37\%$ in Research & Development, $30.34\%$ in Sales, and $4.29\%$ in Human Resources.Gender: $60.0\%$ Male and $40.0\%$ Female.Overtime: $28.30\%$ of the workforce regularly works overtime.Job Roles: Sales Executives, Research Scientists, and Laboratory Technicians are the top three roles, making up over $59\%$ of the company.
* Bivariate Analysis
Monthly Income vs. Attrition: Employees who leave the company have a significantly lower median monthly income compared to those who stay. Low compensation is a strong potential driver of attrition.
Overtime vs. Attrition: Working overtime heavily correlates with leaving. The proportion of employees who exit is drastically higher among those who work overtime compared to those who do not.
Job Satisfaction vs. Attrition: There is a clear inverse relationship. As job satisfaction scores drop (specifically at level 1), the proportion of attrition noticeably spikes, whereas highly satisfied employees (level 4) are much more likely to stay.
* Multivariate Analysis


## Data Preprocessing
*

## Machine Learning Algorithms used
*

## Model Evaluation
*
## Business Recommendations
*
## Conclusion

## References and Links
* Kaggle Dataset : https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset
