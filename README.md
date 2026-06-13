# Heart Disease Prediction using Machine Learning

## Project Overview

This project focuses on predicting heart disease using machine learning classification algorithms. The dataset was preprocessed, analyzed, and used to train multiple models. The performance of each model was evaluated using classification metrics, and the best-performing model was selected based on its results.

---
## Google Colab Notebook

Add your shared Colab notebook link here:

Link (https://colab.research.google.com/drive/1eTk60jE3Xv5eMMp5MNdaoa9-0iwqBKc0?usp=sharing)

## Dataset Source

Heart Disease Dataset (Kaggle)

[https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)

---

## Tools & Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Project Workflow

### Step 1 — Load, Explore & Preprocess

* Loaded the heart disease dataset.
* Checked for missing values.
* Verified data types of all features.
* Removed 723 duplicate records.
* Split the dataset into training and testing sets using an 80:20 ratio.

---

### Step 2 — Feature Engineering

* Performed correlation analysis using a heatmap.
* Identified the relationship between features and the target variable.
* Removed weakly correlated features:

  * fbs
  * chol
* Retained the remaining features for model training.

---

### Step 3 — Train Machine Learning Models

The following classification models were trained:

1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Decision Tree
4. Random Forest
5. Naive Bayes

Training was performed using the training dataset, and predictions were generated on the test dataset.

---

### Step 4 — Model Evaluation & Comparison

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 85.25%   |
| KNN                 | 59.02%   |
| Decision Tree       | 80.33%   |
| Random Forest       | 78.69%   |
| Naive Bayes         | 80.33%   |

Logistic Regression achieved the best overall performance across the evaluation metrics.

---

### Step 5 — Best Model Analysis & Conclusion

#### Best Model

Logistic Regression

#### Performance

* Accuracy: 85.25%
* Precision: 86.49%
* Recall: 88.89%
* F1 Score: 87.67%

#### Confusion Matrix Results

* True Positives (TP): 32
* True Negatives (TN): 20
* False Positives (FP): 5
* False Negatives (FN): 4

The model demonstrated strong predictive performance while maintaining a low number of false negative predictions, making it suitable for heart disease prediction.

---

## Conclusion

1. The dataset was successfully cleaned and prepared for machine learning.
2. Correlation analysis helped identify the most useful predictive features.
3. Five classification models were trained and evaluated.
4. Logistic Regression achieved the highest overall performance.
5. Logistic Regression was selected as the final model for heart disease prediction.

---


