<img width="1920" height="1128" alt="image" src="https://github.com/user-attachments/assets/206d543b-c224-4d5b-acd1-efe2176f8fd3" /># 📘 Student Exam Pass/Fail Predictor

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

## ⚙️ Installation & Usage

### 1️⃣ Clone the repository
```bash
git clone <your-repo-link>
cd <your-repo-folder>
2️⃣ Install dependencies
bash
Copy
Edit
pip install -r requirements.txt
3️⃣ Run the Streamlit App
bash
Copy
Edit
streamlit run app.py
🧑‍💻 Example Usage
Enter Hours Studied (e.g., 6.5)

Enter Sleep Hours (e.g., 7.0)

Select Class Attendance % (e.g., 80)

Click Predict Result

✅ Output: PASS 🎉 or FAIL 📉

📊 Model Performance
The model was evaluated using:

Accuracy

Precision

Recall

F1 Score

(You can add the actual values from your training notebook results.)

📌 Tech Stack
Python 🐍

Scikit-learn 🤖

Streamlit 🌐

Pickle 📦
