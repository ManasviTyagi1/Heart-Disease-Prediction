# ❤ Heart Disease Prediction using Machine Learning

This project focuses on building a machine learning classification model to predict the presence of heart disease using a dataset from UCI. The model is trained on patient medical attributes to assist in early diagnosis and risk prediction.

## 📁 Project Overview

This repository contains:

* A cleaned and preprocessed dataset: heart_disease_uci.csv
* A Jupyter notebook that performs:

  * Exploratory Data Analysis (EDA)
  * Data Preprocessing
  * Model Training and Evaluation
  * Visualization of results

---

## 📊 Dataset

* *Source:* UCI Heart Disease Dataset
* *Filename:* heart_disease_uci.csv
* *Features:*

  * age, sex, cp (chest pain type), trestbps (resting blood pressure), chol (serum cholesterol)
  * fbs (fasting blood sugar), restecg, thalach (maximum heart rate), exang, oldpeak, slope, ca, thal
* *Target:*

  * target: 1 indicates presence of heart disease, 0 indicates absence

---

## 🛠 Tools and Libraries

* *Language:* Python
* *Libraries:*

  * pandas, numpy, matplotlib, seaborn
  * scikit-learn for ML algorithms
  * xgboost (if applicable)

---

## 📈 Workflow

### 1. Exploratory Data Analysis (EDA)

* Checked for missing values
* Analyzed distributions of features
* Correlation matrix to assess feature relationships

### 2. Data Preprocessing

* Label encoding for categorical variables
* Feature scaling using StandardScaler

### 3. Model Building

Trained and evaluated several models:

* Logistic Regression
* Decision Tree
* Random Forest
* Support Vector Machine (SVM)
* K-Nearest Neighbors (KNN)

Evaluation metrics used:

* Accuracy
* Precision, Recall, F1-Score
* Confusion Matrix

---

## 📊 Results and Visualizations

* Confusion matrix for all models
* Accuracy comparison bar chart
* Feature importance (if applicable)
* Model performance metrics summary

---

## 🚀 How to Run

1. *Clone the repository*

   bash
   git clone https://github.com/yourusername/Heart-Disease-Prediction.git
   cd Heart-Disease-Prediction
   

2. *Install required packages*

   bash
   pip install -r requirements.txt
   

3. *Run the notebook*
   Open 10_Heart_Disease_Prediction_Model_Project.ipynb in Jupyter and execute the cells.

---

## 📌 Future Enhancements

* Deploy the model using Streamlit or Flask
* Add hyperparameter tuning for better performance
* Integrate with real-time patient input UI

---

## 🙋‍♂ Author

*Manasvi Tyagi*
AI & ML @ KIET Group of Institutions
