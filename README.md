# Student Exam Score Prediction using Machine Learning

## 📌 Project Overview
This project focuses on analyzing student-related data and predicting **exam performance** using machine learning techniques.  
Exploratory Data Analysis (EDA) is performed to understand patterns in study habits, attendance, sleep, and other factors that affect exam results.

The project implements **Support Vector Machine (SVM)** and **Logistic Regression** models to classify whether a student will pass or fail.

---

## 📂 Dataset Description
- **Dataset Name:** Exam Score Prediction
- **Rows:** 20,000
- **Columns:** 13
- **Target Variable:** `Result` (Pass / Fail)
- **Missing Values:** None
- **Duplicate Values:** None

---

## 🧾 Features Used
- Age  
- Gender  
- Course  
- Study Hours  
- Class Attendance  
- Internet Access  
- Sleep Hours  
- Sleep Quality  
- Study Method  
- Facility Rating  
- Exam Difficulty  

---

## 🔍 Exploratory Data Analysis (EDA)
The following EDA steps were performed:
- Distribution of exam scores
- Study hours vs exam score visualization
- Correlation heatmap
- Checking null values and data types

**Key Insight:**  
Study hours and class attendance show the strongest relationship with exam performance.

---

## ⚙️ Data Preprocessing
- Removed unnecessary columns (`student_id`)
- Label encoding for categorical variables
- Feature scaling using StandardScaler
- Created target column `Result` from exam scores

---

## 🧠 Machine Learning Models
### 1️⃣ Support Vector Machine (SVM)
- Kernel: Linear & RBF
- Accuracy: ~84%
- Performed well with selected important features

### 2️⃣ Logistic Regression
- Accuracy: ~84%
- Stable and interpretable classification model

---

## 📊 Model Evaluation
- Confusion Matrix
- Accuracy Score
- Precision, Recall, F1-score

---

## 🛠️ Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📌 Conclusion
- Student performance depends on multiple factors
- Study hours and attendance are the most influential features
- SVM and Logistic Regression both provide reliable results

---

## 🚀 Future Scope
- Hyperparameter tuning
- Feature selection optimization
- Try ensemble models
- Deploy model using Streamlit

---

## 👩‍💻 Author
**Sukanya Sirpaul**
[SVM1_1766485553.pdf](https://github.com/user-attachments/files/24308967/SVM1_1766485553.pdf)
[Uploading Exam_Score_Prediction.csv…]()
