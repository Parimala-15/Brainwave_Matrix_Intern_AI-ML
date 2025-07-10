# 📰 Fake News Detection using Machine Learning

This project aims to identify whether a given news article is **real or fake** using a supervised machine learning approach. By leveraging natural language processing (NLP) techniques and classification algorithms, it can classify news headlines or article texts with high accuracy.

---

## 📌 Project Overview
Dataset: https://drive.google.com/drive/folders/1tAKatHyuMIRH19hdvmrnsr5yiiuHCXc6?usp=drive_link
Misinformation and fake news have become increasingly prevalent, especially on social media platforms. This Fake News Detection system takes a textual news input and classifies it as **Fake** or **Real**.

🔍 The project uses:
- **TF-IDF vectorization** for feature extraction
- **Logistic Regression** classifier
- **Model serialization** using `joblib`
- Trained on a labeled dataset of real and fake news

---

## ✨ Key Features

- ✅ Cleaned and preprocessed dataset
- ✅ TF-IDF vectorization of text data
- ✅ Logistic Regression model for classification
- ✅ Accuracy evaluation on train/test split
- ✅ Saved model (`model.pkl`) for deployment or API use

---

## 🚀 How It Works

### 1️⃣ Data Preprocessing
- Stopword removal
- Lowercasing
- Removing punctuation and special characters
- Tokenization

### 2️⃣ Feature Extraction
- Uses **TF-IDF (Term Frequency-Inverse Document Frequency)** to convert text into numerical features.

### 3️⃣ Model Training
- A **Logistic Regression** classifier is trained to distinguish fake from real news.

### 4️⃣ Prediction & Evaluation
- The model is evaluated using **accuracy**, **precision**, and **recall** on both train and test sets.

---

## 🧠 Technologies Used

- Python 🐍
- Scikit-learn
- Pandas
- Numpy
- Matplotlib / Seaborn (for optional visualizations)
- Joblib (for model saving)

---

| Metric    | Value |
| --------- | ----- |
| Accuracy  | 0.95  |
| Precision | 0.94  |
| Recall    | 0.96  |


### Clone the repository
git clone https://github.com/Parimala-15/Fake-News-Detection.git
cd Fake-News-Detection

# Install dependencies (if required)
pip install -r requirements.txt


