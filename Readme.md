## Project Summary
This project was completed as part of the Playground Series 3 Episode 14 Challenge organized by Kaggle, an online Data Science Platform known for hosting competitions for the Data Science Community. The challenge focused on predicting the yield of Wild Blueberry. The project involved several steps, as listed below:

1. **Data Preprocessing:**
   - Conducted initial data preprocessing, including handling missing values and applying descriptive tools for data analysis.
   - Handled outliers by changing the top and lower 5 percentile valueswith the median value because of high number of outliers, and simply deleting the outliers 
     could delete valuable information
   - Encoded categorical data using frequency encoding because of high number of classes within each categorical varibale and scaled continuous variables using 
     MinMaxScaler.
   - Separated continuous variables into bins to treat them as categorical variables.

2. **Feature Engineering and Selection:**
   - Created new features to capture additional information about the data and help increase the accuracy during the model Fitting process
   - Generated polynomial and interactive features and and also created some interesting features using domain knowledge which could potentially captivate         
     additional information about the data.
   - Performed feature selection using the p-value approach and Lasso regression.

3. **Model Fitting and Evaluations:**
   - After the features and data was ready, fit three different models: XGBoost, LightGBM, and CatBoost to the data to predict the yield
   - Also ysed an ensemble approach to combine the predictions of the individual models and so that results could generalise better
   - Evaluated the models using Mean Absolute Error (MAE) and Residual Mean Absolute Error (rMAE).
    
