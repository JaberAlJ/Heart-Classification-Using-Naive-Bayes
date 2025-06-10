# ❤️ Heart Classification Using Naive Bayes

This repository implements a Naive Bayes classification model to predict the presence of heart disease using a clinical dataset. It walks through the data analysis and preprocessing pipeline, ending with model training and evaluation.

## ✍️ About the Author
> Written by: [*JaberAlJ*](https://github.com/JaberAlJ)

---

## 1. 📝 Repository Overview

This repository explores a heart disease dataset using the Naive Bayes classification technique. The aim is to accurately classify patients based on clinical features as having heart disease or not.

---

## 2. 📦 Library Imports

Essential Python libraries used in this repository include:

- `pandas` – data manipulation
- `numpy` – numerical operations
- `matplotlib.pyplot`, `seaborn` – data visualization
- `sklearn` – model selection, encoding, scaling, and Naive Bayes implementation

---

## 3. 📊 Dataset Description

The dataset consists of multiple clinical features such as:

- Age
- Sex
- Chest pain type (cp)
- Resting blood pressure (trestbps)
- Cholesterol level (chol)
- Fasting blood sugar (fbs)
- Resting electrocardiographic results (restecg)
- Maximum heart rate achieved (thalach)
- Exercise-induced angina (exang)
- ST depression (oldpeak)
- Slope of the peak exercise ST segment (slope)
- Number of major vessels colored by fluoroscopy (ca)
- Thalassemia (thal)

The target variable is **'target'**, indicating the presence (1) or absence (0) of heart disease.

---

## 4. 🔍 Initial Data Assessment

The initial steps involved:

- Viewing the dataset structure
- Checking data types and missing values
- Analyzing the distribution of the target variable
- Understanding class balance

---

## 5. 🧹 Data Cleaning

Performed:

- Handling of missing values (if any)
- Conversion of data types where needed
- Removal or imputation of anomalous values

---

## 6. 🔢 Data Encoding

Categorical features like `cp`, `thal`, and `slope` were encoded using **Label Encoding** or **One-Hot Encoding** as required to make them suitable for model training.

---

## 7. 🛠️ Data Preparation

Steps included:

- Splitting the dataset into features and labels
- Scaling the features using `StandardScaler`
- Splitting into training and test sets using `train_test_split`

---

## 8. 🤖 Model Selection & Evaluation

- A **Gaussian Naive Bayes** classifier was used.
- The model was trained on the preprocessed data.
- Evaluation metrics included **accuracy**, **confusion matrix**, and **classification report**.
- Visualization of performance metrics was also done to interpret the results.

---

### ✅ Conclusion

Naive Bayes proved to be a simple yet effective model for heart disease classification. With minimal tuning and preprocessing, it delivered reasonable accuracy.
