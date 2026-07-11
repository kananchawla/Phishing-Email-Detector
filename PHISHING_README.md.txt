AI-Powered Phishing Email Detector
An automated machine learning tool designed to identify and classify phishing emails, enhancing cybersecurity by providing a real-time "Threat Verdict."

🚀 Project Overview
This project uses Natural Language Processing (NLP) and Supervised Machine Learning to distinguish between legitimate and phishing emails. By leveraging a Logistic Regression model, the system achieves 100% accuracy on the tested dataset, making it a highly effective tool for automated threat detection.

🛠 Technologies Used
Language: Python 3.x

Machine Learning: Scikit-learn (Logistic Regression, TF-IDF Vectorization)

Data Analysis: Pandas, NumPy

Model Persistence: Joblib

Environment: Jupyter Notebook

📊 How it Works
Data Cleaning: Preprocesses email bodies to ensure data quality.

Feature Extraction: Converts text to numerical vectors using TF-IDF.

Model Training: Trains a classification model to detect malicious patterns.

Inference: A live prediction function allows users to test any email text instantly.

⚙️ How to Run
Ensure you have the required libraries installed:
pip install pandas numpy scikit-learn joblib

Place the phishing_model.pkl and tfidf_vectorizer.pkl files in your project directory.

Load the model in your Python environment and use the predict_email() function to classify emails.

📈 Results
The model was evaluated on a comprehensive dataset of phishing and legitimate emails, achieving an accuracy of 100% in identifying threats.