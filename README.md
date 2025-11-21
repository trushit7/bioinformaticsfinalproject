# Heart Disease Prediction Using Machine Learning

This project evaluates the ability of machine learning models to predict heart disease using routine clinical features. It uses the public UCI Heart Disease dataset and implements a complete, reproducible scikit-learn pipeline including preprocessing, model training, evaluation, and visualization.

# Methods Summary

Preprocessing: StandardScaler + OneHotEncoder via ColumnTransformer
Models: Logistic Regression, Random Forest
Validation: 5-fold stratified cross-validation
Metrics: Accuracy, F1, ROC-AUC
Visualizations: Correlation heatmap, ROC curves, feature importances

# Usage

Clone the repository
Place heart.csv in the project folder
Open notebook in Jupyter or Colab
Run each cell sequentially to reproduce results

# Obtained Result

| Model               | Accuracy  | F1        | ROC-AUC   |
| ------------------- | --------- | --------- | --------- |
| Logistic Regression | 0.787     | 0.817     | 0.871     |
| Random Forest       | *0.803*   | *0.838*   | *0.903*   |

# Contributors

Rudra Maheshbhai Patel
Utsav Ashokbhai Desai
Trushit Mukeshkumar Jaiswal

