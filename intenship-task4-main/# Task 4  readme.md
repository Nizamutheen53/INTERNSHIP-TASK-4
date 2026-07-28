# Task 4 - Classification with Logistic Regression

## Objective

The objective of this project is to build a binary classification model using Logistic Regression to predict whether a breast tumor is Benign or Malignant.

---

## Dataset

Dataset Used:
Breast Cancer Wisconsin Dataset

Rows : 569

Columns : 33

Target Variable:
diagnosis

M = Malignant (1)

B = Benign (0)

---

## Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Project Workflow

1. Import required libraries.
2. Load the dataset.
3. Perform data cleaning.
4. Remove unnecessary columns.
5. Convert target labels into binary values.
6. Split the dataset into training and testing sets.
7. Standardize the feature values.
8. Train the Logistic Regression model.
9. Predict test data.
10. Evaluate the model using:
   - Accuracy
   - Confusion Matrix
   - Precision
   - Recall
   - ROC-AUC Score
11. Tune the decision threshold.
12. Visualize the Sigmoid Function.

---

## Evaluation Metrics

- Accuracy Score
- Precision Score
- Recall Score
- Confusion Matrix
- Classification Report
- ROC-AUC Score

---

## Sigmoid Function

The sigmoid function converts the linear output of Logistic Regression into a probability value between 0 and 1.

Formula:

σ(z) = 1 / (1 + e^(-z))

---

## Threshold Tuning

The default threshold for Logistic Regression is 0.5.

Changing the threshold affects Precision and Recall:

- Higher Threshold increases Precision.
- Lower Threshold increases Recall.

Threshold tuning helps improve model performance based on business requirements.

---

## Project Outcome

Successfully developed a Logistic Regression model capable of classifying breast tumors into Benign and Malignant categories.

The model was evaluated using standard classification metrics and ROC-AUC analysis.

---

## Author

Selvakumaran G
B.Tech Artificial Intelligence and Data Science