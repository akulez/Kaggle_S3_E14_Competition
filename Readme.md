# Kaggle_Playground_S3_E14
This project was completed as part of the Playground Series 3 Episode 14 Challenge organized by Kaggle, an online Data Science Platform known for hosting competitions for the Data Science Community. The challenge focused on predicting the yield of Wild Blueberry. The project involved several steps, as listed below:

1) Data Preprocessing:
Conducted initial data preprocessing, including handling missing values and applying various descriptive tools to analyze the data.
Dealt with outliers by changing only the top and lower 5 percentile values, as deleting the outliers could potentially disadvantage the analysis.
Encoded categorical data using frequency encoding due to the high number of classes within categories.
Utilized MinMaxScaler to scale continuous variables, which were later separated into bins to treat them as categorical variables.

2) Feature Engineering and Selection: Created new features to capture additional information about the existing features.
Generated polynomial and interactive features to explore complex relationships.
Incorporated domain knowledge to add interesting and relevant features.
Performed feature selection using the p-value approach and Lasso regression to retain only the most important features for making predictions.

3) Model Fitting and Evaluations:
Fit models to predict the yield of blueberry based on the prepared data and selected features.
Utilized three different models: XGBoost, LightGBM, and CatBoost.
Employed an ensemble approach to combine the predictions of the individual models, aiming to improve generalization performance.
Evaluated the models using metrics such as Mean Absolute Error (MAE) and Residual Mean Absolute Error (rMAE).
    
