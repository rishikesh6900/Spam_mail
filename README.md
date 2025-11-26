# 📧 Spam Email Classifier (Machine Learning Project)

This project is a machine learning–based **Spam vs Not-Spam Email Classifier** built using:

- **TF-IDF Vectorization** (text → numerical features)
- **Logistic Regression** (classification model)
- **Python + scikit-learn**
- A custom dataset of 50 labeled emails (spam_dataset_50.csv)

The goal of this project is to classify incoming emails as **Spam (1)** or **Ham / Not-Spam (0)** based on the text content.

---

## 🚀 Project Features

- Converts email text into numeric vectors using **TF-IDF**
- Trains a **Logistic Regression classifier**
- Supports prediction on **new custom emails**
- Includes **accuracy**, **confusion matrix**, and **classification report**
- Clean, modular code suitable for beginners
- Small custom dataset included (50 samples)
- Easy to extend using a bigger dataset

---

## 📁 Project Structure

📦 spam-email-classifier
│
├── spam_email_classifier.ipynb # Jupyter notebook with full code
├── spam_dataset_50.csv # 50-sample labeled dataset
└── README.md # Project documentation

---

## 🧠 How the Model Works

### 1️⃣ TF-IDF Vectorization  
- Converts text into numeric vectors  
- Removes English stopwords  
- Assigns each word a weight based on importance

### 2️⃣ Logistic Regression  
- Learns which words are associated with spam
- Computes probability using the sigmoid function
- Predicts **1** if probability ≥ 0.5, else **0**

### 3️⃣ Evaluation  
Model is evaluated using:

- **Accuracy Score**
- **Confusion Matrix**

---

## 💻 Technologies Used

- Python
- Scikit-Learn
- Pandas
- NumPy
- Jupyter Notebook


