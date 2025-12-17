# 🤖 Sarcasm Detection System  

Ever wondered whether a sentence is sarcastic or genuinely serious?  
This project uses **Machine Learning and NLP** to automatically detect sarcasm in text with confidence scores.

Built as a **hands-on ML + Streamlit application**, this project focuses on practical text preprocessing, feature extraction, and real-time prediction.

---

## 🚀 Features
- Detects **Sarcastic vs Regular** sentences
- Uses **TF-IDF + Logistic Regression**
- Clean and interactive **Streamlit UI**
- Displays **confidence levels** for predictions
- Lightweight and fast inference

---

## 🧠 How It Works
1. User enters a sentence
2. Text is cleaned (lowercasing, URL removal, noise filtering)
3. TF-IDF vectorization converts text into numerical features
4. Logistic Regression model predicts sarcasm
5. Confidence probabilities are shown in the UI

---

## 🛠️ Tech Stack
- **Python**
- **Scikit-learn**
- **Pandas**
- **TF-IDF Vectorizer**
- **Logistic Regression**
- **Streamlit**

---

## 📂 Project Structure
```
Sarcasm_Detector/
│
├── app.py
├── train.csv
├── requirements.txt
├── sarcasm_detecror.ipynb
├── .gitignore
└── README.md
