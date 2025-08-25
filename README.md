# 🌳 Decision Tree Pass/Fail Predictor  

This project uses a **Decision Tree Classifier** to predict whether a student will **Pass or Fail** an exam based on study-related features.  
It is also deployed as an **interactive Streamlit web app** for real-time predictions.  

👉 **Try it Live:** [Streamlit App](https://svm-and-decision-tree-tasks---student-pass-or-fail-q3zcwconvf4.streamlit.app/)  

---

## 📌 Project Overview  
The objective of this project is to:  
- Train a **Decision Tree model** on student performance data  
- Predict **Pass/Fail outcomes**  
- Provide an interactive **Streamlit web app** for testing inputs  
- Visualize model behavior with **plots and decision tree graph**  

---

## 📂 Dataset  
The dataset includes the following features:  
- 📖 **Hours Studied**  
- 😴 **Sleep Hours**  
- 🏫 **Attendance Percentage**  
- 🎯 **Pass/Fail Label**  

📄 Example dataset file: `student_exam_tree.csv`  

---

## 📸 Screenshots  

### 🖥️ Streamlit Web App  
The Streamlit web app allows users to input **Hours Studied**, **Sleep Hours**, and **Attendance %**.  
Based on these inputs, the trained Decision Tree model predicts whether the student will **Pass or Fail**.  

![Streamlit App Screenshot](Screenshot%202025-08-25%20170244.png)  

---

## 📊 Visualizations  

### 1️⃣ Distribution of Hours Studied  
Most students studied between **2–8 hours**. Students who studied more hours had a higher chance of passing.  

![Hours Studied Distribution](da352702-8ca3-4ebc-a4c8-308ec99df82f.png)  

---

### 2️⃣ Distribution of Sleep Hours  
Most students reported sleeping between **5–8 hours**. Proper rest also contributed to better results.  

![Sleep Hours Distribution](2fcace71-3841-497d-9017-66bf90d298a7.png)  

---

### 3️⃣ Distribution of Attendance  
Higher attendance strongly correlated with passing the exam. Students with **low attendance** were more likely to fail.  

![Attendance Distribution](1936d2e6-106b-4ca7-a955-f3810dd97120.png)  

---

### 4️⃣ Distribution of Pass/Fail Outcomes  
The dataset is slightly imbalanced, with more students **passing** than failing.  

![Pass/Fail Distribution](7de8e60d-5429-483d-a133-bca3ee1113e4.png)  

---

### 5️⃣ Decision Tree Visualization  
The trained Decision Tree splits data mainly on **Attendance** and **Hours Studied** to decide pass/fail outcomes.  

![Decision Tree](112b38d4-edce-4f47-b756-d7cf5e5d77db.png)  

---

## 📊 Model Evaluation  
The Decision Tree is evaluated using:  
- ✅ Accuracy  
- ✅ Precision  
- ✅ Recall  
- ✅ F1-score  
- ✅ Confusion Matrix  

---

## 📝 Future Enhancements  
- Add more features (assignment marks, quiz scores, etc.)  
- Compare performance with other ML models (Logistic Regression, Random Forest, SVM)  
- Improve interpretability using SHAP values  
- Enhance UI with more interactive plots in Streamlit  

---
