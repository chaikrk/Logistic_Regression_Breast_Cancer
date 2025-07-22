# Breast Cancer Prediction using Logistic Regression

This project implements a Logistic Regression model to predict breast cancer based on the Wisconsin Breast Cancer Diagnostic dataset.

## Project Steps:

1.  **Data Loading**: The dataset is loaded from Kaggle using `kagglehub`.
2.  **Data Preprocessing**: The 'id' column is dropped, and the 'diagnosis' column is mapped to numerical values (Malignant: 1, Benign: 0).
3.  **Data Splitting**: The data is split into training and testing sets (80% training, 20% testing).
4.  **Feature Scaling**: The features are scaled using `StandardScaler` to ensure that all features contribute equally to the model.
5.  **Model Training**: A Logistic Regression model is trained on the scaled training data.
6.  **Model Evaluation**: The model's performance is evaluated using Accuracy Score, Confusion Matrix, and Classification Report.

## Results:

The model's performance is evaluated using the following metrics:

- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)
- 

 ## Report:
               precision    recall  f1-score   support

    Benign (0)       0.97      0.99      0.98        71
    Malignant (1)       0.98      0.95      0.96        43

     accuracy                           0.97       114
    macro avg       0.97      0.97      0.97       114
    weighted avg       0.97      0.97      0.97       114
