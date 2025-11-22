# Loan Approval Prediction

Predict whether a loan application will be approved using a **synthetic, realistic dataset**.  
This project demonstrates **data analysis, feature engineering, and machine learning** for credit risk modeling.

## Dataset Overview
- **Records:** 50,000  
- **Features:** 20 (18 predictors + 1 target + `customer_id`)  
- **Target:** `loan_status` (Approved = 1, Rejected = 0)  
- **Product Types:** Credit Card, Personal Loan, Line of Credit  
- **Missing Values:** None  

## Key Features
- **Demographics:** Age, Occupation Status, Years Employed  
- **Financial Profile:** Annual Income, Credit Score, Credit History Length, Savings/Assets, Current Debt  
- **Credit Behavior:** Defaults on File, Delinquencies, Derogatory Marks  
- **Loan Request:** Product Type, Loan Intent, Loan Amount, Interest Rate  
- **Derived Ratios:** Debt-to-Income, Loan-to-Income, Payment-to-Income  

## Project Workflow
1. **Exploratory Data Analysis (EDA)** – visualize distributions, correlations, and relationships  
2. **Feature Engineering** – calculate ratios, encode categorical features  
3. **Model Training** – Logistic Regression, Decision Tree, Random Forest, XGBoost  
4. **Evaluation Metrics** – Accuracy, F1 Score, ROC-AUC, Feature Importance  
5. **Explainability (Optional)** – SHAP or LIME for model interpretation  
6. **Deployment (Optional)** – Streamlit or Flask application  

## Expected Feature Importance
1. Credit Score  
2. Debt-to-Income Ratio  
3. Delinquencies  
4. Loan Amount  
5. Annual Income  

## Notes
- The dataset is **synthetic** but based on real banking criteria for realistic credit decisions.  
- Safe for **ML practice**, portfolio projects, and exploratory analysis.  
- Not intended for **real-world lending decisions**.  

## License
This project and dataset are licensed under **[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)** — free to use and adapt with credit.
