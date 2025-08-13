# Obesity Classification Using Machine Learning

This project is a machine learning-based system that classifies a person's level of obesity based on their health and lifestyle data. It utilizes three machine learning algorithms—**Random Forest**, **Support Vector Machine (SVM)**, and **Decision Tree**—and automatically selects the best-performing model to generate predictions.

---

## Key Features

- Data preprocessing including Label Encoding and Standard Scaling.
- Dataset split into training and testing sets.
- Model training using three popular ML algorithms.
- Accuracy evaluation and classification reports for each model.
- Confusion matrix visualization before and after hyperparameter tuning.
- Hyperparameter optimization using GridSearchCV to improve model performance.
- Feature importance visualization for models that support it.
- New data prediction using the best-performing model.
- Decoding of predicted labels back to original class names.

---

## Algorithms Used

- **Random Forest Classifier**
- **Decision Tree Classifier**
- **Support Vector Machine (SVM)**

The model with the highest accuracy is selected to classify both the test data and future input data.

---

## Evaluation and Visualization

- **Confusion Matrix**: Shows the performance of each classifier.
- **Classification Report**: Displays precision, recall, and F1-score.
- **Feature Importance**: Visualizes which features contribute most to the prediction (for Random Forest and Decision Tree).

---

## Predicting on New Data

This project supports prediction on new datasets by:

- Preprocessing new inputs with saved encoders.
- Scaling features using the previously fitted scaler.
- Making predictions using the best-performing model.
- Mapping encoded results back to human-readable labels.

---

## Dataset

The dataset used is **ObesityDataSet.csv**, which contains attributes such as:

- Gender
- Family history with overweight
- Physical activity
- Eating habits
- Mode of transportation
- Target label: `NObeyesdad` (obesity level)

---

## Notes

- Encoders for categorical variables are saved and reused when handling new data.
- New data must follow the same structure as the original training data.

---
