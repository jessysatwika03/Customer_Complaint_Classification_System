# 🤖 AI Complaint Classifier

A Machine Learning-powered web application that analyzes customer complaints and automatically predicts complaint categories, confidence scores, urgency levels, and relevant keywords. The system also generates automated responses to support customer service operations.

## 🚀 Features

* Complaint Classification using NLP
* Confidence Score Prediction
* Urgency Detection
* Keyword Extraction
* Automated Response Generation
* Interactive Flask Web Interface
* Real-Time Complaint Analysis

## 🛠️ Technologies Used

**Backend:** Python, Flask

**Machine Learning:** Scikit-learn, LinearSVC, CalibratedClassifierCV, TF-IDF Vectorization

**Data Processing:** Pandas, NumPy

**Frontend:** HTML, CSS

## 📂 Project Structure

```text
Complaint_Classifier/
│
├── complaint_classifier/
│   └── templates/
│       └── index.html
│
├── app.py
├── train_model.py
├── customer_complaints_dataset_extended.csv
├── model.pkl
├── refined_model.pkl
├── vectorizer.pkl
├── requirements.txt
└── README.md
```

## ⚙️ Installation

```bash
git clone <repository-url>
cd Complaint_Classifier
pip install -r requirements.txt
python app.py
```

Open your browser and visit:

```text
http://127.0.0.1:5000
```

## 🔍 Workflow

1. Complaint Text Input
2. Text Preprocessing
3. TF-IDF Vectorization
4. Complaint Classification
5. Confidence & Urgency Analysis
6. Keyword Extraction
7. Automated Response Generation

## 📈 Future Enhancements

* Sentiment Analysis
* Complaint Analytics Dashboard
* User Authentication
* Cloud Deployment
* Multi-language Support

## 👩‍💻 Author

-**Jessy Satwika**
-**Sreethi**

Machine Learning & Data Science Enthusiast
