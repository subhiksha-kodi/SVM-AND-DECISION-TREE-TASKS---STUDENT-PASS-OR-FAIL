# 📘 Student Exam Pass/Fail Predictor

## 🔹 Project Overview  
This project predicts whether a **student will pass or fail an exam** based on:  
- 📖 **Hours Studied**  
- 😴 **Sleep Hours**  
- 🏫 **Class Attendance (%)**  

A **Decision Tree Classifier** was trained on sample student data.  
The model was saved using **Pickle** (`model.pkl`, `scaler.pkl`) and deployed as a **Streamlit Web App**.  

---

## 🚀 Live Demo  
👉 Try the app here: [Student Exam Pass/Fail Predictor](https://svm-and-decision-tree-tasks---student-pass-or-fail-q3zcwconvf4.streamlit.app/)  

---

## 📂 Files in this Repository
- `code.ipynb` → Jupyter Notebook with model training & evaluation.  
- `model.pkl` → Trained Decision Tree model.  
- `scaler.pkl` → Scaler object used for preprocessing.  
- `app.py` → Streamlit app for user-friendly prediction.  

---

## 🧑‍💻 Example Usage
1. Enter **Hours Studied** (e.g., `6.5`)  
2. Enter **Sleep Hours** (e.g., `7.0`)  
3. Select **Class Attendance %** (e.g., `80`)  
4. Click **Predict Result**  

✅ Output: **PASS 🎉** or **FAIL 📉**  

---

## 📊 Model Performance
The model was evaluated using:  
- Accuracy  
- Precision  
- Recall  
- F1 Score  

*(You can add the actual values from your training notebook results.)*  

---

## 📌 Tech Stack
- Python 🐍  
- Scikit-learn 🤖  
- Streamlit 🌐  
- Pickle 📦  
