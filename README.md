# 🌳 Decision Tree Pass/Fail Predictor  

This project uses a **Decision Tree Classifier** to predict whether a student will **Pass or Fail** an exam based on study-related features. It is also deployed as an **interactive Streamlit web app**.  

---

## 📌 Project Overview  
The objective of this project is to:  
- Train a **Decision Tree model** on student data  
- Predict **Pass/Fail outcomes**  
- Provide an easy-to-use **Streamlit web app** for testing inputs  
- Visualize model behavior (tree structure & results)  

---

## 📂 Dataset  
The dataset includes student performance features such as:  
- 📖 **Hours Studied**  
- 😴 **Sleep Hours**  
- 🏫 **Attendance Percentage**  
- 🎯 **Pass/Fail Label**  

📄 Example dataset: `student_exam_tree.csv`  

---

## ⚙️ Installation & Requirements  

### ✅ Requirements  
Make sure you have the following installed:  
- Python 3.8+  
- numpy  
- pandas  
- scikit-learn  
- streamlit  
- matplotlib  

### 📦 Install dependencies  
pip install -r requirements.txt

yaml
Copy
Edit

---

## 🚀 Usage  

### 📥 Clone this repository  
git clone https://github.com/your-username/student-pass-fail-predictor.git
cd student-pass-fail-predictor

shell
Copy
Edit

### ▶️ Run the Streamlit app  
streamlit run app.py

bash
Copy
Edit

### 🌐 Open in browser  
http://localhost:8501/

yaml
Copy
Edit

Or try the hosted app 👉 [Live Demo](https://svm-and-decision-tree-tasks---student-pass-or-fail-q3zcwconvf4.streamlit.app/)  

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
- Add more features (assignments, quiz scores, etc.)  
- Compare with other ML models (Logistic Regression, Random Forest, SVM)  
- Improve explainability with SHAP values  
- Enhance UI with interactive charts in Streamlit  

---
