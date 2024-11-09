# Diabetes Progression Prediction
This project predicts diabetes progression using a Random Forest Regressor on the Diabetes dataset from sklearn.datasets. By analyzing clinical data such as BMI, blood pressure, and age, the model forecasts a quantitative measure of diabetes progression one year after baseline.

## Key Steps
### Data Exploration:
Data is loaded, visualized, and correlations among features are examined.
### Preprocessing: 
Features are scaled to improve model performance.
###Model Training: 
A Random Forest model is trained on 80% of the dataset, with hyperparameters tuned to optimize accuracy.
### Evaluation: 
The model’s accuracy is assessed with Mean Squared Error (MSE) and R² Score, including cross-validation for consistency.
Results Visualization: A plot of actual vs. predicted values illustrates model predictions.
Results
The project demonstrates a data-driven approach to predicting diabetes progression, highlighting key insights and opportunities for improvement.
## Success Rate
The Random Forest Regressor model achieves an R² Score of approximately 0.45 on the test set, meaning it explains about 45% of the variance in diabetes progression. Cross-validation shows consistent performance, with a mean R² Score of 0.43 across folds, indicating reliable prediction accuracy on unseen data.
