
# Loan Default Prediction

This project focuses on predicting loan default risk using a dataset containing information about loans. The dataset includes key features such as home ownership, loan amount, interest rates, and loan status. The goal is to build a machine learning model that can predict whether a loan is low-risk or high-risk.

## Project Overview

The project involves the following steps:
1. **Data Processing & Cleaning**: Cleaning and preparing the loan dataset for model training.
2. **Feature Engineering**: Converting categorical variables and encoding them numerically.
3. **Model Training**: Using a machine learning classifier to predict loan default risk.
4. **Model Evaluation**: Assessing model performance with relevant metrics and techniques.

## Dataset

The dataset consists of 17,205 loan records with the following key features:
- `loan_amount`: Amount of loan taken by the borrower
- `home_ownership`: Whether the borrower owns a home (Categorical)
- `interest_rate`: Interest rate on the loan (Percentage)
- `loan_status`: The risk category of the loan (Categorical)

## Steps Involved

### 1. Data Processing & Cleaning
- Removed null values and handled missing data.
- Converted interest rates from percentage to decimals.
- Categorized loan statuses into `low_risk` and `high_risk`.

### 2. Feature Engineering
- Applied **one-hot encoding** on categorical variables like `home_ownership` and `loan_status` to create numerical features for model training.

### 3. Data Balancing
- Applied **oversampling techniques** like **Random Oversampling** and **SMOTE** to balance the dataset and improve the recall for high-risk loan predictions by 7-12%.

### 4. Model Training
- Used a **Balanced Random Forest Classifier** with 100 estimators to train the model.

### 5. Model Evaluation
- Achieved a balanced accuracy score of **78.85%**.
- Evaluated the model performance using a **confusion matrix** and **classification report**.

## Model Performance

- **Balanced Accuracy**: 78.85%
- **Recall (High-Risk Loans)**: Improved by 7-12% after applying oversampling techniques.

## Requirements

To run the project, ensure that the following Python libraries are installed:

- `pandas`
- `numpy`
- `scikit-learn`
- `imbalanced-learn`
- `matplotlib`
- `seaborn`

You can install the necessary dependencies using:

```bash
pip install -r requirements.txt
```

## Usage

To train and evaluate the model, run the following script:

```bash
python loan_default_prediction.py
```

## License

This project is licensed under the MIT License.

## Acknowledgements

- Thanks to [imbalanced-learn](https://imbalanced-learn.org) for providing tools for balancing the dataset using oversampling techniques.
- Scikit-learn documentation was used for implementing machine learning algorithms and evaluation metrics.
```

Feel free to customize it based on the actual filenames and other specifics of your project.
