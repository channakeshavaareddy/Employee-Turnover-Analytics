# Employee-Turnover-Analytics
Employee Turnover Analytics predicts employee attrition using HR data like satisfaction, workload, and salary. It applies ML models (Logistic Regression, Random Forest, Gradient Boosting) with SMOTE for imbalance. Random Forest performed best, and employees are grouped into risk zones to support retention strategies. 

##  Project Aim
The aim of this project is to analyze employee data and develop a machine learning system to predict employee attrition in an organization. It focuses on understanding the key factors that influence employees leaving, such as satisfaction level, workload, salary, promotions, and tenure. The project involves exploratory data analysis to uncover patterns, clustering techniques to group employees with similar behaviors, and classification models to predict turnover. SMOTE is used to handle class imbalance for better model performance. Finally, employees are categorized into risk zones to help HR teams identify at-risk employees and implement targeted retention strategies to improve workforce stability.

## Steps Involved in the Project:
### Data Collection 
- Loaded HR dataset containing employee attributes such as satisfaction level, working hours, salary, and attrition status.

### Data Cleaning & Preprocessing 
- Checked for missing values, duplicates, and handled categorical variables using encoding techniques.

### Exploratory Data Analysis (EDA) 
- Analyzed patterns and relationships between features and employee attrition using visualizations.

### Feature Selection & Transformation 
- Selected relevant features and converted categorical variables into numerical format.

### Clustering Analysis 
- Applied K-Means clustering to group employees based on satisfaction and evaluation scores.

### Handling Class Imbalance 
- Used SMOTE technique to balance the dataset for better model performance.

### Model Building 
- Trained multiple machine learning models including Logistic Regression, Random Forest, and Gradient Boosting.

### Model Evaluation 
- Evaluated models using accuracy, precision, recall, F1-score, and ROC-AUC metrics.

### Risk Segmentation 
- Classified employees into risk zones (Safe, Low, Medium, High) based on predicted probabilities.

### Insights & Recommendations 
- Derived key insights and suggested retention strategies for HR decision-making.

## Tools, Software, and Libraries Used

**Programming Language:**
- Python 

**Libraries:**
- NumPy – numerical computations  
- Pandas – data manipulation and analysis  
- Matplotlib – data visualization  
- Seaborn – statistical data visualization  
- Scikit-learn – machine learning models and evaluation  
- Imbalanced-learn – handling class imbalance using SMOTE  

**Machine Learning Algorithms Used:**
- Logistic Regression  
- Random Forest Classifier  
- Gradient Boosting Classifier  
- K-Means Clustering  

**Version Control:**
- Git & GitHub – project hosting and version control  

##  Key Visualizations:
### Correlation Heatmap
 ![image alt](https://github.com/channakeshavaareddy/Employee-Turnover-Analytics/blob/main/Screenshots%20(ETA)/Screenshot%202026-04-30%20115424.png)

###  Department vs Attrition and Salary vs Attrition
 ![image alt](https://github.com/channakeshavaareddy/Employee-Turnover-Analytics/blob/main/Screenshots%20(ETA)/Screenshot%202026-04-30%20115612.png)
 ![image alt](https://github.com/channakeshavaareddy/Employee-Turnover-Analytics/blob/main/Screenshots%20(ETA)/Screenshot%202026-04-30%20115700.png)

### Average monthly hours distribution
 ![image alt](https://github.com/channakeshavaareddy/Employee-Turnover-Analytics/blob/main/Screenshots%20(ETA)/Screenshot%202026-04-30%20115839.png)

### Satisfaction level distribution
  ![image alt](https://github.com/channakeshavaareddy/Employee-Turnover-Analytics/blob/main/Screenshots%20(ETA)/Screenshot%202026-04-30%20115848.png)
  
### last evaluation distribution
![image alt](https://github.com/channakeshavaareddy/Employee-Turnover-Analytics/blob/main/Screenshots%20(ETA)/Screenshot%202026-04-30%20115900.png)

### K-Means clustering scatter plot
![image alt](https://github.com/channakeshavaareddy/Employee-Turnover-Analytics/blob/main/Screenshots%20(ETA)/Screenshot%202026-04-30%20115924.png)

### ROC Curve (Logistic Regression)
![image alt](https://github.com/channakeshavaareddy/Employee-Turnover-Analytics/blob/main/Screenshots%20(ETA)/Screenshot%202026-04-30%20115953.png)

### ROC Curve (Random Forest)
![image alt](https://github.com/channakeshavaareddy/Employee-Turnover-Analytics/blob/main/Screenshots%20(ETA)/Screenshot%202026-04-30%20120008.png)

### Gradient Boosting Model Performance
![image alt](https://github.com/channakeshavaareddy/Employee-Turnover-Analytics/blob/main/Screenshots%20(ETA)/Screenshot%202026-04-30%20120023.png)

### Employee Risk Zones
![image alt](https://github.com/channakeshavaareddy/Employee-Turnover-Analytics/blob/main/Screenshots%20(ETA)/Screenshot%202026-04-30%20120037.png)

##  Conclusion

This project focused on analyzing employee data to understand the factors that lead to employee attrition and to build a predictive machine learning model for the same. Using exploratory data analysis, it was observed that key factors such as employee satisfaction level, workload (average monthly hours), number of projects, salary level, and time spent in the company have a strong influence on whether an employee is likely to leave.

To build an effective prediction system, multiple machine learning models were implemented, including Logistic Regression, Random Forest, and Gradient Boosting. Since the dataset had an imbalance between employees who stayed and those who left, the SMOTE technique was applied to improve model learning and performance on the minority class.

After evaluating all models using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC, the Random Forest model performed the best and provided the most reliable predictions. It was able to effectively capture complex relationships between employee attributes and attrition behavior.

In addition to prediction, clustering was used to group employees who left into different behavioral segments, helping to better understand different types of attrition patterns. Finally, employees were categorized into risk zones (Safe, Low Risk, Medium Risk, and High Risk) based on predicted probabilities, which can help HR teams take proactive and targeted retention actions.

Overall, this project demonstrates how machine learning can be applied in real-world HR analytics to support data-driven decision-making, reduce employee turnover, and improve organizational retention strategies.












