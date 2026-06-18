# 🔐 Password Strength Prediction using NLP & Machine Learning

A Machine Learning and Natural Language Processing (NLP) project that predicts the strength of passwords based on textual patterns, character composition, and complexity features.

The model classifies passwords into three categories:

- Weak Password
- Medium Password
- Strong Password

This project utilizes character-level NLP techniques and machine learning algorithms to evaluate password security and help identify weak credentials.

---

## 📌 Project Overview

Passwords are the first line of defense against unauthorized access. Weak passwords significantly increase the risk of security breaches and cyberattacks.

This project applies NLP and Machine Learning techniques to automatically analyze and classify password strength. The model learns patterns from real-world leaked password data and predicts whether a password is weak, medium, or strong.

---

## 🚀 Features

- Extracted password data from a SQLite database
- Performed extensive data cleaning and preprocessing
- Conducted exploratory data analysis (EDA)
- Engineered password complexity features
- Applied character-level TF-IDF vectorization
- Built a multiclass classification model
- Predicted password strength with high accuracy
- Evaluated model performance using standard metrics

---

## 📂 Dataset

The dataset contains passwords along with their corresponding strength labels.

### Strength Labels

| Label | Strength |
|---------|---------|
| 0 | Weak |
| 1 | Medium |
| 2 | Strong |

The dataset is derived from publicly available leaked password collections commonly used for password strength analysis.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- SQLite
- Matplotlib
- Seaborn
- Scikit-Learn
- NLP
- TF-IDF Vectorization
- Logistic Regression
- Jupyter Notebook

---

## 📊 Project Workflow

### 1. Data Collection
- Extracted password records from a SQLite database.
- Loaded data into a Pandas DataFrame.

### 2. Data Cleaning
- Removed missing values.
- Eliminated duplicates.
- Verified target labels and data quality.

### 3. Exploratory Data Analysis
- Analyzed password length distribution.
- Examined class distribution.
- Investigated password composition patterns.

### 4. Feature Engineering
Generated meaningful password features such as:
- Password Length
- Number of Uppercase Characters
- Number of Lowercase Characters
- Number of Digits
- Number of Special Characters

### 5. NLP Processing
Applied Character-Level TF-IDF Vectorization to capture password patterns and complexity.

### 6. Model Training
Used Logistic Regression for multiclass classification.

### 7. Model Evaluation
Evaluated the model using:
- Accuracy Score
- Confusion Matrix
- Classification Report

---

## 📈 Results

The model achieved approximately:

**Accuracy: ~80%**

This demonstrates the effectiveness of combining NLP techniques with machine learning for password strength prediction.

---

## 📁 Repository Structure

```text
NLP_Password_Strength/
│
├── NLP_password_strength_.ipynb
├── README.md
└── password_data.sqlite
```

---

## 💡 Example Predictions

| Password | Predicted Strength |
|-----------|------------------|
| 123456 | Weak |
| password123 | Medium |
| P@ssW0rd!2024 | Strong |

---

## 🎯 Future Improvements

- Deploy the model using Streamlit
- Build a real-time password strength checker
- Implement Deep Learning models (LSTM/GRU)
- Add Password Entropy Analysis
- Improve model performance with advanced NLP techniques

---

## 🔗 Project Repository

Repository Link:

https://github.com/guptasakshi06/NLP_Password_Strength

---

## 👩‍💻 Author

**Sakshi Gupta**

B.Tech Student | Data Analytics & Machine Learning Enthusiast

GitHub: https://github.com/guptasakshi06

---

⭐ If you found this project useful, consider giving the repository a star!
