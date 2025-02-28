# Credit Card Approval Prediction System

## Overview
This project is a machine learning solution that predicts credit card application approvals based on applicant financial data. It employs comprehensive data preprocessing, feature engineering, and classification techniques to identify the key factors influencing approval decisions.

## Data Preprocessing & Feature Engineering
- **Categorical Encoding:** Converts categorical variables (e.g., Credit History, Prior Default) into numerical format.
- **Scaling:** Applies normalization (using MinMaxScaler) to numerical features for uniformity.
- **Data Splitting:** Divides the dataset into training and test sets (e.g., 70/30 split) to ensure reliable model evaluation.

## Model Training & Evaluation
- **Model Used:** Logistic Regression is primarily used for prediction.
- **Performance Metrics:**
  - **Accuracy:** 86.96%
  - **Precision:** 90.91%
  
These results demonstrate the model’s effectiveness in correctly classifying approved applications while minimizing false positives.

## Technical Terms
- **Accuracy:** The ratio of correct predictions to total predictions.
- **Precision:** The ratio of true positive predictions to all positive predictions.

## How to Run
1. **Dependencies:** Install Python libraries such as `pandas`, `numpy`, `scikit-learn`, etc.
2. **Execution:** Open and run the Jupyter Notebook to perform data preprocessing, train the logistic regression model, and evaluate its performance.
3. **Review:** Analyze the output metrics and feature importance to gain insights into the approval factors.

## Conclusion
This project illustrates the power of data-driven decision-making in the financial domain, providing a robust tool for credit card approval prediction.
