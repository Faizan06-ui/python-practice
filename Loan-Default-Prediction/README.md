# Loan Default Prediction using Deep Learning

## Overview
This Deep Learning project predicts whether a borrower is likely to default on a loan using Lending Club loan data. The project applies data preprocessing, feature engineering, class imbalance handling and neural network modeling using TensorFlow and Keras.

The goal of the project is to help financial institutions identify high-risk borrowers and improve loan approval decisions using predictive analytics. 

---

## Objectives
- Analyze loan applicant data
- Identify patterns related to loan default
- Handle class imbalance in the dataset
- Build a deep learning model for loan default prediction
- Evaluate model performance using classification metrics and ROC-AUC score

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow
- Keras
- Jupyter Notebook

---

## Dataset Information
The dataset contains financial and credit-related information such as:
- Credit Policy
- Loan Purpose
- Interest Rate
- Installment Amount
- Annual Income
- Debt-to-Income Ratio
- FICO Score
- Revolving Balance
- Revolving Utilization
- Public Records
- Loan Repayment Status

The dataset contains 9,578 loan records with 14 features. 

## Dataset

The dataset used in this project is not included due to GitHub file size limitations.

The project was created for educational and learning purposes.

---

## Project Workflow

### 1. Exploratory Data Analysis
Performed:
- Data inspection
- Missing value analysis
- Class distribution analysis
- Correlation heatmap visualization

### 2. Feature Engineering
- Converted categorical variables using one-hot encoding
- Removed highly correlated features
- Performed feature scaling using StandardScaler

### 3. Handling Class Imbalance
Applied class weighting to address imbalanced loan default classes before training the neural network.

### 4. Deep Learning Model Development
Built a neural network using TensorFlow and Keras with:
- Dense layers
- Batch Normalization
- Dropout layers
- Adam optimizer
- Binary Crossentropy loss
- Early Stopping

### 5. Model Training
- Used validation split during training
- Applied EarlyStopping to reduce overfitting
- Monitored validation loss and AUC performance

### 6. Model Evaluation
Evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC-AUC Score

---

## Deep Learning Architecture

The neural network consists of:
- Input Layer
- Dense Layer (128 neurons)
- Batch Normalization
- Dropout Layer
- Dense Layer (64 neurons)
- Batch Normalization
- Dropout Layer
- Dense Layer (32 neurons)
- Output Layer (Sigmoid Activation)

The model contains approximately 13,569 trainable parameters. 

---

## Model Performance

| Metric | Score |
|---|---|
| Accuracy | 65% |
| ROC-AUC Score | 0.67 |

The model achieved moderate predictive performance for identifying loan default risk. 

---

## Key Insights
- Loan default data was highly imbalanced
- Feature scaling improved neural network training stability
- Early stopping helped reduce overfitting
- Class weighting improved minority class prediction performance

---

## Project Structure

Loan-Default-Prediction/
│
├── data/
├── notebooks/
│   └── loan_default_prediction.ipynb
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
- Use advanced deep learning architectures
- Apply hyperparameter tuning
- Experiment with SMOTE oversampling
- Deploy the model using Streamlit or Flask
- Improve ROC-AUC performance using ensemble techniques

---

## Author
Faizan Khurshid