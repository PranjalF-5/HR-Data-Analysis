# HR-Data-Analysis

# HR Analytics Dataset - README

## Overview
This dataset contains detailed information on employee demographics, work experience, job roles, and various other features. It is primarily used for HR analytics tasks, such as predicting employee attrition, analyzing job satisfaction, and identifying trends in business travel and department distribution.

## Dataset Information
The dataset consists of **1,470** employee records with **35 columns** representing various attributes such as age, attrition status, job role, education, satisfaction levels, and more.

### Key Columns:
- **Age**: Age of the employee.
- **Attrition**: Whether the employee has left the company (`Yes`) or not (`No`).
- **BusinessTravel**: Frequency of business travel (`Travel_Rarely`, `Travel_Frequently`, `Non-Travel`).
- **DailyRate**: Daily salary of the employee.
- **Department**: Department where the employee works (`Sales`, `Research & Development`, `Human Resources`).
- **DistanceFromHome**: Distance from home to work in kilometers.
- **EducationField**: Field of education (`Life Sciences`, `Medical`, `Marketing`, `Technical Degree`, `Human Resources`).
- **EnvironmentSatisfaction**: Employee’s satisfaction with their work environment (rating: 1-4).
- **JobRole**: Employee’s job role (`Sales Executive`, `Research Scientist`, `Manager`, etc.).
- **MonthlyIncome**: Monthly salary of the employee.
- **YearsAtCompany**: Total years spent by the employee at the company.
- **YearsInCurrentRole**: Years spent by the employee in their current role.
- **WorkLifeBalance**: Work-life balance rating (rating: 1-4).

### Unique Value Summary:
- **BusinessTravel**: 
  - `Travel_Rarely`
  - `Travel_Frequently`
  - `Non-Travel`
  
- **EducationField**:
  - `Life Sciences`
  - `Medical`
  - `Marketing`
  - `Technical Degree`
  - `Human Resources`
  - `Other`
  
- **JobRole**:
  - `Sales Executive`
  - `Research Scientist`
  - `Laboratory Technician`
  - `Manufacturing Director`
  - `Healthcare Representative`
  - `Manager`
  - `Sales Representative`
  - `Research Director`
  - `Human Resources`
  
- **MaritalStatus**:
  - `Single`
  - `Married`
  - `Divorced`

- **Department**:
  - `Sales`
  - `Research & Development`
  - `Human Resources`

### Data Types:
- **int64**: Age, DailyRate, DistanceFromHome, EmployeeCount, EnvironmentSatisfaction, etc.
- **object**: Attrition, BusinessTravel, Department, EducationField, JobRole, MaritalStatus, etc.

## Usage
This dataset can be used for the following analyses:
- **Attrition Prediction**: Using features such as age, education field, business travel, and environment satisfaction to predict whether an employee will leave the company.
- **Job Satisfaction Analysis**: Analyzing job satisfaction based on education field, role, and department.
- **Work-Life Balance Analysis**: Understanding how work-life balance varies across departments and roles.


