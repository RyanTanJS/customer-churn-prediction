# customer-churn-prediction

## 1. Project Overview
This project develops a machine learning model to predict customer churn for a telecommunications company.
Churn is a major buisness problem, by retaining customers through predicting which are most likely to churn the company could save money

## 2. Dataset
- Public Telco Churn dataset (Kaggle / IBM)

- 7,043 customer records

- 21 features (demographics, contract details, charges, services)

## 3. Objective
- Predict customer churn using machine learning

- Identify key drivers of churn

- Provide business insights to guide retention strategies

## 4. Methods
- Exploratory Data Analysis (EDA)

- Feature Engineering

- Model Training and Comparison:

    - Logistic Regression (scaled and unscaled)

    - Random Forest

    - XGBoost (tuned)

- Model Explainability with SHAP

## 5. Model Performance
| Model                            | ROC AUC | F1 Score | Precision | Recall |
|----------------------------------|---------|----------|-----------|--------|
| Logistic Regression (unscaled)   | 0.80    | 0.61     | 0.65      | 0.57   |
| Logistic Regression (scaled)     | 0.39    | 0.61     | 0.65      | 0.57   |
| Random Forest                    | 0.82    | 0.55     | 0.62      | 0.49   |
| XGBoost (tuned)                  | 0.84    | 0.58     | 0.65      | 0.52   |

## 6. Key insights
- Tenure: Shorter-tenure customers are more likely to churn.

- Contract Type: Month-to-month contracts have higher churn risk.

- Internet Service: Fiber optic customers churn more than DSL or no internet.

- Monthly Charges: Higher charges are linked to higher churn.

## 7. Business Implications
- Target short-tenure customers with loyalty offers.

- Promote longer-term contracts to reduce churn.

- Offer incentives for high-charge customers on short contracts.

## 8. Next Steps
- Deploy model and provide to retention team as a scoring tool.

- Monitor model performance over time.

## 9. Pacakage Versions 
