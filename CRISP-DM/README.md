# House Price Prediction Model for California Homes

## Project Overview

This project aims to build a **House Price Prediction Model** to predict the sale price of homes in California. The model uses pre-sale information such as structure details, location, nearby schools, and listing text.

## Data

The project utilizes a dataset of homes sold in California in 2020. The data includes features like Address, Year built, Lot size, number of Bedrooms and Bathrooms, school scores and distances, and listing summary.

## Methodology

The project follows the CRISP-DM methodology, covering the following phases:

1.  **Business Understanding**: Defining the project objective, success criteria, and constraints.
2.  **Data Understanding**: Exploring the dataset, identifying data quality issues, and understanding variable distributions.
3.  **Data Preparation**: Handling missing values, encoding categorical features, and scaling numerical features.
4.  **Modeling**: Training a regression model (Random Forest in this case) on the preprocessed data.
5.  **Evaluation**: Assessing the model's performance using relevant metrics.

## Evaluation Metric

The primary evaluation metric used is the **Root Mean Squared Error (RMSE) between the logarithm of the predicted value and the logarithm of the observed sales price (Log RMSE)**.

## Key Results (from latest evaluation)

*   **Log-RMSE**: {{log_rmse:.4f}}
*   **Median APE**: {{median_ape:.3%}}

