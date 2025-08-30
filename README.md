Sales Data Analysis & Business Insights



I built a machine learning model to predict product profits for a retail store.

The dataset was collected manually by me from a store in Erode (name withheld at the owner’s request). 
It contained product details such as price, supplying city, and pattern. Using this data, I developed a predictive model to estimate sales profit.

I trained the data on four robust algorithms — XGBoost, Lasso Regression, Ridge Regression, and Linear Regression — and found that
 XGBoost performed best, explaining nearly 50% of the variance in the target variable.

Before training, I performed data preprocessing and exploratory data analysis (EDA), uncovering actionable business insights 
such as the most profitable supplier cities and product patterns. These insights led to several practical and implementable 
recommendations for improving profitability.

During the model training phase, I noticed initial performance was lower than expected. I addressed this by performing 
hyperparameter tuning with GridSearchCV, which significantly improved accuracy. I also carried out residual analysis, 
confirming the model’s reliability as most residuals were small, centered around zero, and followed a random distribution.

To deepen my understanding, I conducted SHAP analysis to identify the most influential features contributing to predictions, 
and cross-checked these with XGBoost’s built-in feature importance.

This project not only delivered valuable business insights but also strengthened my skills in:
    *Feature engineering (including frequency encoding and one-hot encoding)
    *Model evaluation and tuning
    *Interpreting machine learning models using explainability tools

Overall, this Profit Prediction project gave me hands-on experience with real-world data and helped me understand both the technical and business sides of machine learning.
