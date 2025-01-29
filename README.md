# Spam-Mail-Detection
# 📧 Spam Mail Detection  

## 📌 Overview  
This project is a **machine learning-based spam mail classifier** that identifies whether an email is spam or not. It utilizes **TF-IDF vectorization** to convert text into numerical features and applies a **Logistic Regression model** for classification.  

## 🚀 Features  
- **Preprocessing:** Text conversion using TF-IDF vectorization  
- **Machine Learning Models:** Logistic Regression, Naïve Bayes, Support Vector Machine (SVM), Random Forest  
- **Accuracy Evaluation:** Accuracy score metric  
- **Dataset Splitting:** Training and testing data split  

## 🛠️ Tech Stack  
- **Programming Language:** Python  
- **Libraries Used:**  
  - `numpy` – For numerical computations  
  - `pandas` – For handling and processing datasets  
  - `scikit-learn` – Used for:  
    - `train_test_split` – Splitting data into training and testing sets  
    - `TfidfVectorizer` – Converting text data into numerical features using TF-IDF  
    - `LogisticRegression`, `MultinomialNB`, `SVC`, `RandomForestClassifier` – Various classification models  
    - `accuracy_score` – Evaluating model performance  
