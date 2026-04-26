Overview: In this phase, the preprocessed dataset is used to train and evaluate multiple machine learning models.

Steps Performed:

Data Loading
Loaded the preprocessed dataset from Phase 1.
Feature and Label Separation
Split dataset into features (X) and target variable (Label).
Train-Test Split
Data split into training and testing sets (80:20 ratio).
Feature Scaling
Applied StandardScaler to normalize the data.
Scaling performed after splitting to avoid data leakage.
Model Training Trained multiple models:
K-Nearest Neighbors (KNN)
Logistic Regression
Decision Tress Classifier
Random Forest Classifier
Hyperparameter Tuning
Used Elbow Method to find optimal value of K for KNN.
Model Evaluation
Evaluated models using:
Accuracy Score
Confusion Matrix
Classification Report
Output

Trained models
Performance comparison of models
Elbow method graph
Conclusion Multiple models were trained and evaluated
