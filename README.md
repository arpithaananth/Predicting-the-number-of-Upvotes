# Prediction of Number of Upvotes

### Work Flow:
1. Checked for the presence of null values
2. Dropped the 'ID' and 'username' features as they do not add any value in terms of prediction
3. Checked the Skewness
4. Rectified the skewness by cube-root transformation
5. Checked the correlation between features
6. Encoded the Categorical to Numeriacl data using get_dummies
7. Normalization using Standard Scalar
8. Comparsion between various Regressors
9. Prediction is done based on the RandomForest Regressor which has given the best Regressor Score

The Target Variable has not been normalized, as a result higher RMSE values are reflected. 
