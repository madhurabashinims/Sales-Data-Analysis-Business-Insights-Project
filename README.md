# Sales Data Analysis & Business Insights

I built a machine learning model to predict product profits for a retail store.

The dataset was collected manually by me from a store in Erode (name withheld at the owner’s request). It contained product details such as price, supplying city, and product pattern. Using this data, I developed a predictive model to estimate sales profit.

## Project Highlights

### Dataset:
Proprietary retail sales data (manually collected).

### Objective: 
Predict product-level profit and extract actionable business insights.

### Algorithms Used:

* Linear Regression

 * Ridge Regression

* Lasso Regression

* XGBoost

### Best Model: 
XGBoost, explaining ~50% of the variance in profit.

## Methodology

### Data Preprocessing

Handled missing values, outliers, and categorical encoding (frequency encoding & one-hot encoding).

Feature engineering to capture product/supplier-level insights.

### Exploratory Data Analysis (EDA)

Identified most profitable supplier cities and high-performing product patterns.

Visualized trends in sales and profitability.

### Model Training & Tuning

Initial models had low accuracy.

Improved performance using GridSearchCV hyperparameter tuning.

Residual analysis confirmed model reliability (residuals ~0 and randomly distributed).

### Model Explainability

Applied SHAP analysis to interpret feature influence.

Cross-validated with XGBoost’s feature importance for robust insights.

## Results & Insights

XGBoost significantly outperformed baseline regression models.

Business insights revealed supplier-city combinations and product patterns with highest profitability potential.

Delivered data-driven recommendations for improving profit margins.

## Skills Strengthened

* Data Preprocessing & Feature Engineering

* Model Selection & Hyperparameter Tuning

* Model Explainability (SHAP, feature importance)

* Business-oriented Data Analysis

## Future Work

Extend dataset with time-series elements for sales trend forecasting.

Deploy the model with a simple React/Flask frontend for real-time predictions.

<img width="928" height="944" alt="image" src="https://github.com/user-attachments/assets/186e1c69-9de4-49c7-a20c-ca2e1c215ed9" />
<img width="1026" height="547" alt="image" src="https://github.com/user-attachments/assets/45774025-55ec-4ee4-856e-8ed66dd61ec1" />
<img width="639" height="547" alt="image" src="https://github.com/user-attachments/assets/21bec1ae-92ae-43bc-bfa9-3f03095cb4d0" />



