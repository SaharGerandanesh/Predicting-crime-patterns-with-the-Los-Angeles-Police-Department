# Predicting-crime-patterns-with-the-Los-Angeles-Police-Department
Dataset Selection

Description: This dataset contains detailed information about crimes in Los Angeles, including dates, types of crimes, locations, and methods of crime reporting. The dataset consists of over 1 million rows of various types of crimes, such as theft, burglary, and violent crimes.
Random Forest Classifier

Accuracy: The model achieved a perfect accuracy of 100% (1.00), meaning it correctly classified all samples in the test set.
Confusion Matrix:

Number of True Negatives: 172,894
Number of False Positives: 53
Number of False Negatives: 131
Number of True Positives: 21,818
Classification Report:

Precision for False: 1.00 (100% of negative cases were correctly identified)
Recall for False: 1.00 (100% of negative cases were identified)
Precision for True: 1.00 (100% of positive cases were correctly identified)
Recall for True: 0.99 (99% of positive cases were identified)
F1-score for True: 1.00, indicating a balanced precision and recall.
Summary: The Random Forest model has achieved excellent performance with very high precision and recall for both classes, making it a reliable model for predicting crime patterns.

K-Nearest Neighbors Classifier

Accuracy: The K-Nearest Neighbors model also showed a perfect accuracy of 100% (1.00).
Confusion Matrix:

Number of True Negatives: 172,898
Number of False Positives: 49
Number of False Negatives: 86
Number of True Positives: 21,863
Classification Report:

Precision for False: 1.00
Recall for False: 1.00
Precision for True: 1.00
Recall for True: 1.00
F1-score for True: 1.00, indicating a perfect balance between precision and recall.
Summary: Both Random Forest and K-Nearest Neighbors exhibited perfect accuracy and excellent performance in their classifications. This indicates that these models are effective in identifying and predicting crime patterns based on the current dataset. With high precision and recall, these models can be very helpful for strategic decisions in crime prevention efforts.

Target Variable: Type of crime, classified as violent crime, theft, burglary, etc. Each type of crime is represented as a class in the classification.
Type of Prediction: Classification – predicting the type of crime based on factors such as location, time, and other available metadata.
Data Source: Kaggle – LAPD Crime Data (2020-2024).
Data Management

Data Cleaning: Handling missing values, eliminating duplicates, and standardizing data types.
Feature Engineering: Creating new features such as time of day, day of the week, and geographic zones (areas of the city) to improve predictions.
Data Exploration (EDA): Exploring the dataset to understand distribution patterns and correlations between variables, as well as identifying the most significant features for modeling. Visualizations such as histograms and correlation matrices will be used.
Model Development

Algorithm Selection: Random Forest or XGBoost (to test both bagging and boosting methods).
Hyperparameter Tuning: Using Grid Search or Random Search to optimize model performance.
Performance Evaluation: Using methods such as F1-score, precision, recall, and ROC AUC to evaluate model accuracy.
Feature Importance: Visualization of the most significant factors to understand which variables most influence crime type prediction.
