# HealthDiagnosisAIAssistant


# 🩺 Health Diagnosis AI Assistant

**Capstone Project – AIDI 1003**  
**Student:** Varsha Reghu (100930107)  
**Instructor:** Noopa Jagadeesh  

---

## 🧠 Project Overview

This capstone project focuses on developing an AI-driven web application capable of predicting common diseases like **Diabetes** and **Heart Disease** based on user input. The system leverages machine learning models to evaluate medical parameters and deliver real-time diagnostic suggestions.

The goal is to demonstrate a functional **Minimum Viable Product (MVP)** integrating front-end prediction forms, backend AI models, and a sample chatbot-ready SQLite database to support basic healthcare conversations.

---

## 🌐 Live Demos

- 🔹 [Heart Disease Prediction](#) *(replace with actual deployment link if hosted)*
- 🔹 [Diabetes Prediction](#)

---

## 🚀 Features

- 🔬 Predicts risk of **Heart Disease** and **Diabetes** using trained ML models
- 🌐 Web interface with simple form-based user input
- 🗃️ SQLite database for chatbot interaction testing
- 🧪 Uses SVM and other ML classifiers (accuracy ≥ 82% for Parkinson's prototype)
- 🧩 Modular design for easy expansion (e.g., add more diseases)

---

## 📁 Project Components

```
capstone_project/
├── cardiac.html                    # Web interface for heart disease prediction
├── diabetes.html                   # Web interface for diabetes prediction
├── capstone individual report 5.docx  # Progress documentation by Varsha Reghu
├── chatbot_db.sqlite               # SQLite database (for chatbot integration - not uploaded here)
├── README.md                       # Project summary (this file)
```

---

## 🔧 Technologies Used

- **Frontend:** HTML5, Bootstrap (for styling and layout)
- **Backend Models:** Trained locally (SVM, Decision Trees, etc.)
- **Database:** SQLite for chatbot question-answer pairs
- **Languages:** Python (for model training), SQL (for database setup)

---

## 📊 Dataset & Model Summary

- **Heart Disease & Diabetes datasets** sourced from public health repositories (e.g., UCI)
- **Features included:**
  - Glucose, Blood Pressure, Cholesterol (Diabetes)
  - Age, Sex, Chest Pain, Thalassemia, etc. (Heart Disease)
- **Model Accuracy** (prototype stage): 
  - Parkinson's Detection (SVM): **82%**
  - Heart & Diabetes: Testing pending full integration

---

## 📚 Key Individual Contributions

- 📂 Designed and implemented a sample **SQLite database** with 50+ chatbot queries
- 🧠 Created a working schema with fields like `Query`, `Response`, `Intent`, and `Context`
- ⚙️ Preprocessed Parkinson’s dataset and trained initial model with solid baseline performance
- 🧪 Participated in testing and feedback cycles for integrated components

---

## 💡 Challenges & Solutions

| Challenge | Solution |
|----------|----------|
| Structuring flexible chatbot queries | Used normalized schema design with intent categorization |
| Identifying diverse query-response pairs | Collaborated with team to gather realistic user interactions |
| Integration with MVP chatbot | Designed SQLite independently for smooth plug-in |

---

## 🧭 Next Steps

- Expand database with more user intents and responses  
- Optimize backend queries for performance  
- Link SQLite logic to front-end chatbot component  
- Train and validate models for heart and diabetes prediction at scale

---

## 🧠 Reflection

> *“This capstone helped me apply AI tools to a real-world healthcare problem. I strengthened my skills in SQLite and model prototyping, and learned how collaboration enables faster development and integration.”*  
– **Varsha Reghu**

---

## 📝 License

This project is for academic use only.

