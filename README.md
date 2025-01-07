# House Price Predictor 🏡
## Predicting House Prices in Ames, Iowa

Inspired by Zillow's Zestimate model, my team and I evaluated several machine learning optimization models to build a house price predictor. This project goes through a dataset containing predictors describing features of houses in Ames, Iowa.

### ⭐️ Key highlights of the project:
- Pre-processing the data to reduce data dimentionality and convert it to a more suitable form to build models upon
- Imputing missing values of variables by comparing different imputation methods (Univariate Imputation using Mean vs Multivariate Imputation by Chained Equations)
- Visualizing the data to form an initial hypothesis on what features of the house we think affect price the most
- Feature engineering (PCA and Forward Selection) to pick the most impactful predictors
- Creating a baseline model to compare performance of tuned machine learning models to
- Training KNN, decision trees, random forest, and lasso models and tuning these models to improve their performance before picking the best prediction model
- Ultimately picked the random forest model as our best prediction model due to to its low RMSE score and its ability to show predictors that have the most affect on house prices
