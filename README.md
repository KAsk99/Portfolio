# Customer Lifetime Value (CLV) Prediction

## This work has been created in accordance with requirements of the BSc (Hons) Data Science Degree Apprenticeship with BPP and was conducted using an open-sourced dataset

This project focuses on predicting Customer Lifetime Value (CLV) using machine learning techniques, with the aim of providing actionable insights for data-driven decision-making. By leveraging Python’s powerful data science libraries, the project integrates data preparation, analysis, visualization, and predictive modeling in an efficient and scalable workflow.

## Project Overview

### Objective:
The primary goal of this project is to build a predictive model to estimate Customer Lifetime Value (CLV) based on historical customer data, enabling businesses to:

- Segment high-value customers.
- Optimise marketing strategies.
- Personalise customer experiences.

### Approach:
We used Python to preprocess data, derive meaningful features, and train a linear regression model to predict CLV. Visualizations were employed to understand data patterns and model performance, ensuring clarity and accuracy throughout.

### Dataset

**Size**: 10,000 customer records.

**Format**: CSV file.

**Key Variables**:

- Demographic data (e.g., Gender, Geography).
- Financial metrics (e.g., Balance, Estimated Salary).
- Customer behavior data (e.g., Tenure, Number of Products, Loyalty Points).

### Key Features

**Data Cleaning:**

- Removed redundant columns (e.g., Customer ID, Surnames).
- Imputed missing values.
- Handled outliers through transformations.

**Feature Engineering:**

- Derived Customer Lifetime Value (CLV) from key financial metrics.
- Created new features like loyalty points per year of tenure.

**Predictive Modeling:**

- Built and validated a linear regression model using Scikit-learn.
- Evaluated using metrics: R², MAE, and MSE.

**Data Visualization:**

- Correlation heatmaps to identify feature relationships.
- Pair plots and distribution plots to explore patterns.
- Residual and scatter plots to assess model performance.

### Tools & Libraries

**Development Environment:**

- Jupyter Notebook: Interactive platform for code, visualization, and documentation.

**Key Libraries:**

- Pandas: Data cleaning, manipulation, and transformation.
- Scikit-learn: Machine learning and evaluation metrics.
- Seaborn & Matplotlib: Data visualization and insights.

### Workflow

**Data Loading:**
Imported the dataset using Pandas from a locally stored CSV file.

**Data Preparation:**

- Cleaned and transformed raw data.
- Encoded categorical variables and standardised numerical features.

**Exploratory Data Analysis (EDA):**

- Visualised feature relationships and patterns.
- Identified and resolved multicollinearity using correlation heatmaps.

**Predictive Modeling:**

- Split data into training (80%) and testing (20%) sets.
- Trained and evaluated a linear regression model.

**Results Interpretation:**

- Analysed model performance using evaluation metrics.
- Presented feature importance to highlight key drivers of CLV.

### How to Run

**Prerequisites:**
Ensure you have the following installed:

- Python (3.8 or later)
- Jupyter Notebook
- Required libraries (see requirements.txt)

**Steps:**
1) Clone this repository:
```
git clone https://github.com/your-username/CLV-Prediction.git
cd CLV-Prediction
```
2) Install dependencies:
```
pip install -r requirements.txt
```
3) Open the Jupyter Notebook:
```
jupyter notebook
```
4) Run the notebook step by step to reproduce the results.

### Results

**Key Findings:**

- High-CLV customers typically have higher account balances, longer tenures, and more loyalty points.
- Features like balance, tenure, and loyalty points were the strongest predictors of CLV.

**Model Performance:**

R²: 0.85
MAE: 300.45
MSE: 125,678.90

**Visualizations:**

- Correlation heatmaps revealed multicollinearity, guiding feature selection.
- Residual plots confirmed model assumptions.

### Future Work

**1) Model Improvements:**

- Explore non-linear models like Random Forests or Gradient Boosting.
- Incorporate additional features for better predictions.

**2) Data Enrichment:**

- Use external datasets to enhance insights (e.g., customer demographics, market trends).

**3) Deployment:**

- Develop a web-based interface for real-time CLV predictions.
