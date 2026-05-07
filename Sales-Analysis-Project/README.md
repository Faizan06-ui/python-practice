# Sales Analysis Project

## Overview
This project performs exploratory data analysis and visualization on apparel sales data using Python. The analysis focuses on identifying sales trends, customer groups, state-wise performance and time-based sales patterns.

The project was built using Pandas, Matplotlib, and Seaborn for data cleaning, analysis and visualization. 

---

## Objectives
- Analyze sales performance across different Australian states
- Identify top-performing customer groups
- Study monthly and weekday sales trends
- Visualize sales distributions and patterns
- Perform data cleaning and preprocessing

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Dataset Information
The dataset contains:
- Date
- Time
- State
- Customer Group
- Units Sold
- Sales Amount

The dataset includes 7,560 records of apparel sales transactions from October 2020 to December 2020. 

---

## Project Workflow

### 1. Data Wrangling
- Checked missing values
- Removed null values
- Verified date consistency
- Converted date columns into datetime format

### 2. Data Analysis
Performed:
- Descriptive statistics
- State-wise sales analysis
- Group-wise sales analysis
- Monthly sales analysis
- Weekday sales analysis

### 3. Data Visualization
Generated:
- Bar charts
- Sales distribution histograms
- Box plots
- Group-wise comparison charts
- Time-based sales visualizations

---

## Key Insights
- Victoria (VIC) recorded the highest total sales
- Men and Women categories generated the highest revenue
- December showed stronger sales performance compared to previous months
- Sales distribution showed several high-value outliers

---

## Project Structure

Sales-Analysis-Project/
│
├── data/
├── notebooks/
│   └── sales_analysis.ipynb
├── outputs/
├── README.md
└── requirements.txt

---

## How to Run

1. Clone the repository
2. Install dependencies

pip install -r requirements.txt

3. Open the notebook

jupyter notebook

4. Run all cells

---

## Future Improvements
- Build an interactive dashboard using Streamlit or Power BI
- Add predictive sales forecasting
- Deploy the project as a web application
- Integrate real-time sales analytics

---

## Author
Faizan Khurshid