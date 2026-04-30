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



















