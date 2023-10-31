# House Price Predictor 🏡
## Predicting House Prices in Ames, Iowa

Inspired by Zillow's Zestimate model, my team and I evaluated several machine learning optimization models to build a house price predictor. This project goes through a dataset containing variables/predictors describing features of houses in Ames, Iowa.

### ⭐️ Key highlights of the project:
- Pre-processing the data to reduce data dimentionality and convert it to a more suitable form to build models upon
- Imputing missing values of variables by comparing different imputation methods (Univariate Imputation using Mean vs Multivariate Imputation by Chained Equations)
- Visualizing the data to form an initial hypothesis on what features of the house we think affect price the most
- Feature engineering (PCA and Forward Selection) to pick the most impactful predictors
- Creating a baseline model to compare performance of tuned machine learning models to
- Training tuned KNN, pruned decision trees, random forest, and tuned lasso models to pick the best prediction model while looking out for bias-variance trade-offs
- Ultimately picked the random forest model as our best prediction model due to to its low RMSE score and its ability to show predictors that have the most affect on house prices

### 🔎 Here is a link to the project report for a deeper look
[Project Report](https://drive.google.com/file/d/1r-WBKyk_H3IFA25h3kzNHxJp3GYaMjyz/view?usp=share_link)

### 🔎 Here is a link to the project presentation 
[Project Presentation](https://drive.google.com/file/d/1wjM7aSuYMEN7yl99CNUap3FvT0RLhtOs/view?usp=share_link)
