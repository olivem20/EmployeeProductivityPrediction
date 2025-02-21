# Employee Productivity Analysis 🚀  

## Overview  
This project analyzes **employee productivity** to identify key factors that contribute to efficiency and success. Using **machine learning models**, we explore how variables like **salary, work hours, experience, job role, and department** impact an employee's **performance score**.  

## Objectives  
- Determine **which qualities make employees productive and efficient**.  
- Identify **the best traits of top-performing engineers**.  
- Compare **factors influencing productivity across job titles and departments**.  
- Analyze **gender-based trends** in productivity and success.  

## Dataset  
The dataset includes various employee attributes such as:  
✔ **Demographics:** Age, Gender, Education Level  
✔ **Work Factors:** Monthly Salary, Work Hours, Overtime, Sick Days, Projects Handled  
✔ **Job Role:** Department, Job Title, Years at Company  
✔ **Employee Engagement:** Satisfaction Score, Training Hours, Promotions  
✔ **Performance Score:** The target variable for predicting productivity  

## Data Preprocessing  
- **Label Encoding** for categorical variables (Gender, Education Level).  
- **One-Hot Encoding** for department and job title to allow ML models to process categorical data.  
- **Feature Scaling** for numerical variables using **StandardScaler** to normalize data.  

## Machine Learning Models  
Three **Linear Regression models** were developed to analyze productivity:  

1️⃣ **General Employee Productivity Model**:  
   - Analyzes all employees across departments.  
   - Identifies **salary** as the most important factor.  

2️⃣ **Department-Based Model**:  
   - Examines performance **within different departments**.  
   - Helps determine which departments have the most productive employees.  

3️⃣ **Job Title-Based Model**:  
   - Focuses on **how different job roles impact performance**.  
   - Engineers and Developers show **higher productivity trends**.  

## Key Findings 🔍  
📈 **Higher salaries lead to better productivity.**  
📉 **Long work hours and overtime negatively impact productivity.**  
⚖ **Employee satisfaction has a weaker correlation with performance than expected.**  
👩‍💻 **Different departments and job titles show varying productivity trends.**  
🎓 **Higher education levels do not necessarily improve productivity.**  
