# LUNG-CANCER-PREDICTION-LOGISTIC-REGRESSION-MODEL
PREDICTS THE LUNG CANCER RISK LEVEL OF THE PATIENT THROUGH LOGISTIC REGRESSION 
Lung Cancer Risk Prediction
Project Overview

This project aims to predict the risk of lung cancer using machine learning techniques. The objective was to analyze patient health factors and identify whether a person is likely to have lung cancer.

Initially, an unsupervised learning approach (Clustering) was used to explore natural groupings in the dataset. The expectation was that patients with similar risk factors would form meaningful clusters representing different lung cancer risk levels.

However, clustering results showed that the risk factors were distributed across all clusters, indicating that the algorithm was unable to clearly separate patients into meaningful risk groups.

Because of this limitation, a supervised learning approach was adopted.

Approach
1. Clustering (Initial Attempt)

Clustering techniques were applied to identify hidden patterns in patient health features.

However:

The clusters did not clearly represent different lung cancer risk levels.

Similar risk factors appeared across multiple clusters.

This indicated that clustering was not suitable for accurate prediction in this dataset.

Therefore, clustering was treated as an exploratory step rather than the final solution.

2. Logistic Regression (Final Model)

To improve prediction accuracy, Logistic Regression was used as the primary model.

Logistic regression is well suited for binary classification problems, such as predicting whether lung cancer is present or not.

The model was trained using patient health attributes and evaluated using performance metrics.

Model Evaluation

The model performance was evaluated using:

F1 Score

Recall Score

These metrics are more suitable than accuracy for medical datasets where class imbalance may exist.

Model Results:

F1 Score: 0.36

Recall Score: Calculated during evaluation

The relatively low F1 score indicates that the dataset or feature set may require further improvement for better predictive performance.

Future Improvements

Possible improvements for this project include:

Feature engineering to extract stronger health indicators

Handling class imbalance

Trying advanced models such as:

Random Forest

Gradient Boosting

XGBoost

Hyperparameter tuning

Technologies Used

Python

Pandas

NumPy

Scikit-learn

Matplotlib / Seaborn

Jupyter Notebook

Conclusion

This project demonstrates the process of experimenting with both unsupervised and supervised machine learning techniques to analyze lung cancer risk prediction.

While clustering did not produce meaningful separations, logistic regression provided a baseline predictive model and highlighted areas for further model improvement.
