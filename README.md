###### 🚢 **Predicting Titanic Survival with Machine Learning: A Historical Data Case Study**

Applying machine learning to history — predicting passenger survival on the Titanic using Logistic Regression and real-world classification techniques.

---

### 📌 Project Overview

This project analyzes the Titanic dataset to build a **classification model** that predicts whether a passenger survived based on features such as age, class, gender, and embarkation port. It demonstrates the end-to-end workflow of supervised learning while offering insights from a historical dataset.

The case study combines **data preprocessing, feature engineering, model training, and evaluation**, strengthening core machine learning concepts through practical application.

---

### 🎯 Objectives

* Clean and prepare raw Titanic data for classification
* Engineer meaningful features from categorical and numerical attributes
* Train and evaluate a **Logistic Regression** model
* Implement a user-friendly interface for survival prediction
* Interpret results using standard classification metrics

---

### 🗂️ Dataset

The dataset includes records for 800+ Titanic passengers, with details such as:

* 👤 **Passenger Info**: Age, Sex, Class, Fare, Embarkation
* 🛳️ **Travel Details**: Pclass, Ticket, Cabin (mostly missing)
* 🎯 **Target Variable**: Survived (0 = No, 1 = Yes)

---

### 🔍 Key Highlights of the Analysis

#### ✅ Data Cleaning & Preprocessing

* Dropped irrelevant columns: *PassengerId, Name, Ticket*
* Filled missing values:

  * *Age*: median imputation
  * *Embarked*: mode imputation
* Removed *Cabin* due to excessive null values

#### 🛠️ Feature Engineering & Encoding

* Converted categorical variables (*Sex, Embarked*) using One-Hot Encoding
* Standardized feature input structure for consistent modeling

#### 🤖 Model Building — Logistic Regression

* Implemented **LogisticRegression** from Scikit-learn
* Split data (80% train / 20% test)
* Trained model on engineered features to predict survival probabilities

#### 📈 Model Evaluation

* Evaluated with **Accuracy, Precision, Recall, F1-Score**
* Generated **Classification Report & Confusion Matrix**
* Compared performance between training and testing sets

#### 🧠 Interactive Prediction Interface

* Developed an input form for hypothetical passenger data
* Model outputs predicted survival likelihood instantly

---

### 🛠 Tools & Technologies

* **Python**
* **pandas, numpy** – data handling
* **matplotlib, seaborn** – visualization
* **scikit-learn** – modeling & evaluation
* **Jupyter Notebook** – development & storytelling

---

### 💡 Conclusion

This project shows how **Logistic Regression** can be applied to real-world binary classification problems using historical data. By preparing, visualizing, and modeling the Titanic dataset, it highlights:

* The role of features like gender, class, and age in survival outcomes
* Practical classification modeling techniques
* Data-driven storytelling inspired by history

A strong foundational project for anyone beginning their machine learning journey.

---

### 🔮 Future Enhancements

* Apply **cross-validation** & hyperparameter tuning
* Benchmark against **Random Forest, SVM, KNN**
* Build a full **Streamlit or Flask web app** for live predictions
