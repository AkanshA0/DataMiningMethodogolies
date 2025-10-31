# KDD: Bank Marketing (Term Deposit Subscription)

This notebook demonstrates the **Knowledge Discovery in Databases (KDD)** methodology applied to the **Bank Marketing dataset** (`bank-additional-full.csv`). The goal is to predict whether a bank client will subscribe to a term deposit and to uncover meaningful customer patterns.

## KDD Methodology Phases

The notebook follows the KDD process:

1.  **Selection**: Loading the data, identifying the target variable (`y`), candidate predictors, and excluding leakage features like `duration`.
2.  **Preprocessing**: Handling missing values (treating "unknown" as NaN), encoding categorical variables, standardizing numeric features, and splitting the data into stratified train/validation sets.
3.  **Transformation**: Creating simple derived features to potentially improve model performance.
4.  **Data Mining**: Training and evaluating supervised models (Logistic Regression, Random Forest, Gradient Boosting) using stratified cross-validation and focusing on ROC AUC and PR AUC due to class imbalance. It also includes an exploration of customer segments using KMeans clustering on reduced features.
5.  **Interpretation / Evaluation**: Analyzing model results, identifying key features using permutation importance, and exploring the trade-offs between precision and recall using a threshold sweep. Segment-level insights from the KMeans clustering are also presented.

## Dataset

The dataset used is the classic Bank Marketing dataset (`bank-additional-full.csv`), which contains information about a bank's marketing campaigns and client subscription to term deposits.

## Key Findings

*   The Gradient Boosting model performed best among the evaluated supervised models based on ROC AUC and PR AUC.
*   Permutation importance highlighted the most influential features for predicting term deposit subscription.
*   KMeans clustering revealed distinct customer segments with varying term deposit subscription rates, providing potential targets for tailored marketing strategies.

Note:  Ensure you have the `bank-additional-full.csv` dataset in the `/content/bank_marketing_dataset/` directory or update the `data_path` variable in the notebook.
