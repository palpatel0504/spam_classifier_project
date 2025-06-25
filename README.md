
# 📩 SMS Spam Classifier

A **machine learning-based web app** that classifies text messages as **SPAM** or **HAM** using Natural Language Processing and scikit-learn.  
🔧 Built by **Pal Patel** as part of an AI Internship submission.

---

## 👨‍💻 Developer Info

**Pal Rakesh Patel**  
🎓 B.E. Computer Engineering  
🏫 SVIT Vasad, Class of 2026  
💡 Passionate about AI/ML, Python, and practical software solutions.

---

## 💡 Project Overview

This project is a complete end-to-end implementation of a **Spam Detection System** that:

- Cleans and processes SMS messages
- Converts text into numerical features using **TF-IDF**
- Uses **Naive Bayes** for classification
- Presents a beautiful, responsive **Streamlit GUI**

The app predicts whether a user-entered message is **Spam** or **Ham** (not spam).

---

## 🛠️ Tech Stack

| Component       | Tools/Libraries              |
|----------------|------------------------------|
| Programming     | Python 3.10+                 |
| NLP             | NLTK, Regex, TF-IDF Vectorizer |
| ML Model        | scikit-learn (Naive Bayes)   |
| GUI             | Streamlit                    |
| Serialization   | joblib                       |

---

## 📁 Project Structure

📦 spam_classifier_project/
├── spam_classifier.ipynb # Jupyter Notebook for training & testing
├── app.py # Streamlit-based GUI
├── spam_model.pkl # Trained ML model
├── vectorizer.pkl # TF-IDF vectorizer
├── requirements.txt # Python dependencies
└── README.md # Project readme file (this one!)

## ▶️ How to Run the Project

### 🔹 Step 1: Clone or Download

```bash
git clone https://github.com/palpatel/spam-classifier.git
cd spam-classifier


Step 2: Create & Activate Virtual Environment

python -m venv venv
source venv/bin/activate     # For Mac/Linux
.\venv\Scripts\activate      # For Windows


Step 3: Install Dependencies

pip install pandas numpy scikit-learn streamlit nltk joblib


Step 4: Run the App
streamlit run app.py

Your browser will open at:
👉 http://localhost:8501

🔍 How It Works
Input: User types a message

Clean: The message is processed with NLP

Vectorize: TF-IDF converts it to numerical form

Predict: Trained Naive Bayes model gives output

Output: "SPAM" or "HAM" is displayed on the UI


📸 Sample Screenshot



<img width="725" alt="Screenshot 2025-06-25 at 9 56 33 PM" src="https://github.com/user-attachments/assets/5cf74d64-32d3-4c77-a84c-1930566d70c8" />



<img width="668" alt="Screenshot 2025-06-25 at 9 56 54 PM" src="https://github.com/user-attachments/assets/da7313ff-fee9-425c-b824-e8c97a93715a" />







📌 Final Notes
✅ This project is ready for internship/demo submission.
📁 Keep your .pkl files in the same folder as app.py.
💡 You can customize UI color and layout in app.py.

✨ Developed with dedication by Pal Patel
