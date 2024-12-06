# Telecommunication-Customer-Churn-Prediction

## Overview

This project focuses on predicting customer churn in the telecom industry using machine learning algorithms. By analyzing customer data, the model identifies patterns and key factors contributing to churn, enabling businesses to make data-driven decisions to retain customers.

## Project Workflow

1. **Data Preprocessing**

   - Cleaned and encoded the dataset to prepare it for analysis.
   - Handled missing values and performed feature engineering.

2. **Exploratory Data Analysis (EDA)**

   - Visualized relationships between features and churn.
   - Conducted correlation analysis to identify significant predictors.

3. **Algorithm Selection**

   - Considered multiple models: Naïve Bayes, Logistic Regression, Random Forest, and XGBoost.

4. **Model Building and Evaluation**

   - Trained models and evaluated their performance using metrics like Accuracy, Recall, Precision, and F1-Score.
   - Focused on Recall to prioritize identifying potential churners.

5. **Model Tuning**

   - Applied hyperparameter tuning to optimize model performance.
   - Used SMOTE to handle class imbalance in the dataset.

6. **Visualization**

   - Created insightful plots using Matplotlib and Plotly for feature importance, correlations, and model comparisons.

## Key Features Analyzed

- **Numerical Features**: Tenure, MonthlyCharges, TotalCharges
- **Categorical Features**: Contract type, Payment method, Internet service type

## Results

The models were compared based on Accuracy, Recall, Precision, F1-Score, and ROC-AUC. Random Forest and XGBoost showed strong performance, with XGBoost achieving the best balance of metrics.

## Tools and Technologies

- **Programming Language**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Plotly, Imbalanced-learn

## Conclusion

This project demonstrates the importance of machine learning in predicting customer churn and highlights the significance of metrics like Recall in business applications. The findings provide actionable insights for customer retention strategies.

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/vrutika-prajapati/Telecommunication-Customer-Churn-Prediction.git

2. Install requierd packages:
   ```bash
   pip install -r requirements.txt
3. Run the analysis script:
   ```bash
   python churn_prediction.py
## Dataset

The dataset used in this project contains customer demographics, account information, and usage patterns.

## Acknowledgements

Thanks to the open-source community and publicly available datasets that enabled this analysis.


