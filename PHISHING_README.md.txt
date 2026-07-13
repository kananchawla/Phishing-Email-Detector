# AI-Powered Phishing Email Detector
**Student:** Kanan Chawla

## 🚀 Project Overview
An automated machine learning tool designed to identify and classify phishing emails, enhancing cybersecurity by providing a real-time "Threat Verdict."

## 🛠 Technologies Used
* **Language**: Python 3.x
* **Machine Learning**: Scikit-learn (Logistic Regression, TF-IDF)
* **Interface**: Gradio (for real-time testing)

## 📊 How it Works
1. **Data Cleaning**: Preprocesses email bodies for quality.
2. **Feature Extraction**: Converts text to numerical vectors using TF-IDF.
3. **Model Training**: Logistic Regression model to detect malicious patterns.

## 🌐 Live Demo
You can test the model live here: [https://964acf5be995504877.gradio.live](https://964acf5be995504877.gradio.live)
*(Note: This link is active while my local environment is running.)*

## 🧪 Test Results & Validation
To demonstrate the model's accuracy, I tested it against both malicious and legitimate email samples:

**1. Phishing Email Detection:**
![Phishing Test Result](## 🧪 Test Results & Validation
To demonstrate the model's accuracy, I tested it against both malicious and legitimate email samples:

**1. Phishing Email Detection:**
![Phishing Test Result]()

**2. Legitimate Email Detection:**
![Legitimate Test Result](Screenshot 2026-07-13 120155.png)

*The model successfully classifies these emails by combining a keyword-based heuristic filter with a Logistic Regression AI core.*
