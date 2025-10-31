# SEMMA: Diabetes Classification

This notebook demonstrates a machine learning workflow for diabetes classification following the SEMMA methodology (Sample, Explore, Modify, Model, Assess).

**Project Goal:** To build and evaluate a classification model to predict diabetes based on diagnostic measurements.

**Phases:**

1.  **Sample:** Load the dataset and create train/validation/test splits while maintaining class proportions.
2.  **Explore:** Analyze the data for schema, missingness, ranges, outliers, feature distributions, and correlations.
3.  **Modify:** Preprocess the data by handling missing values and scaling features.
4.  **Model:** Train and evaluate multiple classification models using stratified cross-validation.
5.  **Assess:** Provide a comprehensive performance summary, including visual diagnostics like ROC curves and confusion matrices, and analyze model behavior.

**Dataset:** The dataset used is the Pima Indians Diabetes Database.

**Models Explored:**
*   Logistic Regression
*   Random Forest Classifier
*   Gradient Boosting Classifier

The notebook proceeds through each of these phases, providing code and explanations for each step.
