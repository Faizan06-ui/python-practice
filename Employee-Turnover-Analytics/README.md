# Employee Turnover Analytics

## Overview
This Machine Learning project analyzes employee turnover patterns and predicts the likelihood of employees leaving a company. The project uses Exploratory Data Analysis (EDA), clustering techniques, class imbalance handling, and predictive machine learning models to identify at-risk employees and recommend retention strategies.

The project aims to help organizations improve employee retention by understanding the factors influencing employee attrition. 

---

## Objectives
- Analyze employee turnover trends
- Identify important factors affecting employee attrition
- Perform employee clustering using K-Means
- Handle class imbalance using SMOTE
- Train and compare multiple machine learning models
- Predict employee turnover probability
- Recommend retention strategies

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Jupyter Notebook

---

## Dataset Information
The dataset contains employee-related features such as:
- Satisfaction Level
- Last Evaluation
- Number of Projects
- Average Monthly Hours
- Time Spent at Company
- Work Accidents
- Promotions
- Department
- Salary Level
- Employee Turnover Status

The dataset contains 14,999 employee records with 10 features. 

---

## Project Workflow

### 1. Data Preprocessing
- Checked missing values
- Verified data types
- Encoded categorical variables
- Performed train-test split

### 2. Exploratory Data Analysis
Performed:
- Correlation analysis
- Heatmap visualization
- Distribution plots
- Employee project count analysis
- Employee turnover analysis

### 3. Employee Clustering
Used K-Means clustering to group employees who left the company into 3 clusters based on:
- Satisfaction Level
- Last Evaluation

Cluster analysis helped identify:
- Dissatisfied employees
- High-performing employees
- Employees needing growth opportunities

### 4. Handling Class Imbalance
Applied SMOTE (Synthetic Minority Oversampling Technique) to balance the employee turnover classes before model training.

### 5. Model Training and Evaluation
Trained and compared:
- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier

Evaluation metrics used:
- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC Score
- Confusion Matrix
- 5-Fold Cross Validation

---

## Model Performance

| Model | ROC-AUC Score |
|---|---|
| Logistic Regression | 0.81 |
| Random Forest | 0.99 |
| Gradient Boosting | 0.99 |

Random Forest achieved the best performance with approximately 99% ROC-AUC score. 

---

## Key Insights
- Employee satisfaction level strongly affects turnover
- Employees with low satisfaction are more likely to leave
- High-performing employees may leave due to lack of growth opportunities
- Recall is the most important metric because failing to identify at-risk employees can negatively impact the organization

---

## Retention Strategy
Employees were categorized into:
- Safe Zone (Green)
- Low-Risk Zone (Yellow)
- Medium-Risk Zone (Orange)
- High-Risk Zone (Red)

This helps organizations prioritize employee retention efforts effectively. 

---

## Project Structure

Employee-Turnover-Analytics/
│
├── data/
├── notebooks/
│   └── employee_turnover_analysis.ipynb
├── outputs/
├── README.md
└── requirements.txt

---

## How to Run

1. Clone the repository

2. Install dependencies

pip install -r requirements.txt

3. Open Jupyter Notebook

jupyter notebook

4. Run all notebook cells

---

## Future Improvements
- Deploy the model using Streamlit or Flask
- Add real-time employee turnover prediction
- Build HR analytics dashboard
- Integrate deep learning models
- Automate retention recommendations

---

## Author
Faizan Khurshid