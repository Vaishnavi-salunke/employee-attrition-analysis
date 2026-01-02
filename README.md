# Employee Attrition Analysis & Prediction

## Project Overview
Employee attrition is a major challenge for organizations as it leads to loss of talent, increased hiring costs, and reduced productivity.  
This project performs an end-to-end analysis of employee data to identify key drivers of attrition and builds a machine learning model to predict whether an employee is likely to leave.

---

## Dataset
- IBM HR Analytics Employee Attrition Dataset
- 1,470 employee records
- 35 features including Age, MonthlyIncome, YearsInCurrentRole, JobRole, and OverTime
- Target variable: Attrition (Yes / No)

---

## Tools & Technologies
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Environment:** Jupyter Notebook, VS Code  
- **Version Control:** Git & GitHub  

---

## Exploratory Data Analysis (EDA)

### Univariate Analysis
- Distribution of age, income, and tenure
- Attrition count comparison (Yes vs No)

### Bivariate Analysis
- MonthlyIncome vs Attrition
- Age vs Attrition
- YearsInCurrentRole vs Attrition

### Key Insights
- Employees with lower monthly income showed higher attrition
- Younger employees were more likely to leave
- Employees with fewer years in their current role had higher attrition

---

## Machine Learning Model

### Objective
Predict whether an employee will leave the organization.

### Model Used
- Logistic Regression

### Workflow
- Feature selection
- Train-test split
- Model training
- Model evaluation

### Results
- Accuracy: ~80%
- Most influential features:
  - MonthlyIncome
  - Age
  - YearsInCurrentRole

---

## Conclusion
This project demonstrates how data analysis and machine learning can support HR teams in identifying attrition risks and making data-driven retention strategies.

---

## Project Structure

---

##  Future Scope
- Try advanced models (Random Forest, XGBoost)
- Hyperparameter tuning
- Deploy using Streamlit or Flask

---

## Author
**Vaishnavi Salunke**  
Aspiring Data Analyst / Data Scientist


