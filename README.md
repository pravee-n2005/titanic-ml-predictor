# 🚢 Titanic Survival Prediction - Machine Learning Project

This project predicts the survival of Titanic passengers using machine learning techniques. It is built using the famous Titanic dataset from Kaggle and demonstrates data cleaning, feature engineering, model training, evaluation, and prediction using a Random Forest classifier.

![titanic](https://upload.wikimedia.org/wikipedia/commons/f/fd/RMS_Titanic_3.jpg)

---

## 🔍 Overview

The goal of this project is to build a binary classification model that can predict whether a passenger survived the Titanic disaster based on features like age, sex, ticket class, etc.

---

## 📁 Dataset

The dataset used is from the [Kaggle Titanic Challenge](https://www.kaggle.com/c/titanic/data).

- `train.csv`: Contains labeled training data (passenger info + survival status)
- `gender_submission.csv`: Sample submission format used for testing predictions

---

## 🧰 Tools & Technologies

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn (for visualization)
- Jupyter Notebook / Google Colab

---

## ⚙️ Features Used

- `Pclass`: Ticket class
- `Sex`: Gender
- `Age`: Age of the passenger
- `SibSp`: No. of siblings/spouses aboard
- `Parch`: No. of parents/children aboard
- `Fare`: Fare paid
- `Embarked`: Port of embarkation

Missing values are handled and categorical variables are encoded.

---

## ✅ Model & Accuracy

- **Model Used:** Random Forest Classifier
- **Accuracy Achieved:** ~81% on test data

---

## 📊 Workflow

1. **Data Loading**
2. **Data Cleaning**
3. **Exploratory Data Analysis**
4. **Feature Engineering**
5. **Model Training & Evaluation**
6. **Prediction & Submission File Creation**

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/titanic-ml-predictor.git
   cd titanic-ml-predictor
