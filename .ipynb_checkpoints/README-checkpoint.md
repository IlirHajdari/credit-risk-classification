# Credit Risk Analysis

## Description

This project applies **logistic regression** to analyze credit risk by predicting loan default likelihood. Using **scikit-learn** and **Pandas**, the model classifies loans as either **healthy (0)** or **high-risk (1)** based on key financial indicators.

## Summary

### Part 1: Data Preparation

The dataset was preprocessed to create training and testing sets.

#### Key Deliverables:

- Load `lending_data.csv` into a **Pandas DataFrame**.
- Define the **labels (`y`)** from the `loan_status` column.
- Define the **features (`X`)** using all other columns.
- Split the dataset into **training and testing sets** using `train_test_split`.

### Part 2: Logistic Regression Model

A logistic regression model was trained to classify loans as either **healthy or high-risk**.

#### Key Deliverables:

- Train a **logistic regression model** using `X_train` and `y_train`.
- Predict loan status (`0` or `1`) using `X_test`.
- Evaluate the model’s performance.

### Part 3: Model Evaluation

The model's performance was assessed using standard classification metrics.

#### Key Deliverables:

- Generate a **confusion matrix** to analyze predictions.
- Print a **classification report** with:
  - **Accuracy Score**: Measures overall model correctness.
  - **Precision Score**: Measures correctness of positive (high-risk) predictions.
  - **Recall Score**: Measures how well the model detects high-risk loans.
- Answer: "How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?"

### Part 4: Credit Risk Analysis Report

A report was written to summarize the model’s performance and provide a recommendation.

#### Key Deliverables:

- **Overview**: Explain the purpose of the analysis.
- **Results Summary** (bulleted list):
  - **Accuracy Score**
  - **Precision Score**
  - **Recall Score**
- **Final Recommendation**:
  - Justification for **using or not using** the model in a financial setting.
  
## Requirements

### Tools and Libraries

- **Python**
- **Jupyter Notebook**
- **Pandas**
- **scikit-learn**
- **Matplotlib**

## Contact Information

For questions or additional information, reach out to me at:

- **Email:** ilir.hajdari111@gmail.com
