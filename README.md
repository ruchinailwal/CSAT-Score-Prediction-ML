# 📊 Customer Support Analytics & CSAT Prediction

## 📌 Project Overview
This project focuses on predicting customer satisfaction (CSAT score) using machine learning techniques based on customer service interaction data. The goal is to analyze key factors affecting customer experience and build a predictive classification model.

---

## 📊 Problem Statement
To predict customer satisfaction scores (ranging from 1 to 5) using features such as communication channel, issue category, agent performance, response time, and interaction details.

---

## 🛠️ Tools & Technologies
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## 📁 Project File
- 📒 [Customer_Support_Analytics_CSAT_Prediction.ipynb](Customer_Support_Analytics_CSAT_Prediction.ipynb)

---

## 🔍 Approach
- Data Cleaning and Preprocessing  
- Handling Missing Values  
- Feature Engineering (Response Time Calculation)  
- Exploratory Data Analysis (EDA)  
- Model Building and Evaluation  

---

## 🤖 Models Used
- Logistic Regression  
- Decision Tree  
- Random Forest  

---

## 📈 Results
- Achieved ~71% accuracy after hyperparameter tuning  
- Model performance affected due to class imbalance  

---

## 💡 Key Insights
- Majority of CSAT scores are high (class imbalance present)  
- Models are biased towards the majority class (score = 5)  
- Accuracy alone is not a reliable evaluation metric in this case  

---

## ⚠️ Limitations
- Imbalanced dataset  
- Poor prediction performance for minority classes (1–4)  

---

## 🚀 Future Improvements
- Apply SMOTE to handle class imbalance  
- Improve feature engineering  
- Try advanced models and class weighting techniques  

---

## 📌 Conclusion
This project demonstrates how machine learning can be used to analyze customer service data and predict satisfaction levels. It highlights the importance of handling class imbalance for better model performance.
