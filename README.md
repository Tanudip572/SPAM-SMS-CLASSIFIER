# 📩 SMS Spam Detection using Machine Learning

A Machine Learning-based application that classifies SMS messages as **Spam** or **Ham (Not Spam)** using Natural Language Processing (NLP) techniques and supervised learning algorithms.

## 📌 Project Overview

Spam messages are unwanted messages that can contain advertisements, phishing links, or fraudulent content. This project uses NLP and Machine Learning to automatically identify whether an SMS message is spam or legitimate.

The model is trained on a labeled SMS dataset and deployed using Streamlit for real-time predictions.

---

## 🚀 Features

* Detects Spam and Ham messages.
* Text preprocessing and cleaning.
* Natural Language Processing (NLP) techniques.
* TF-IDF Vectorization.
* Machine Learning-based classification.
* Interactive Streamlit web application.
* Real-time SMS prediction.

---

## 📊 Dataset

The dataset used in this project is the SMS Spam Collection Dataset.

Features:

* `label` → Spam or Ham
* `message` → SMS text content

Dataset contains thousands of labeled SMS messages used for training and evaluation.

---

## 🔧 Data Preprocessing

The following preprocessing steps were applied:

* Convert text to lowercase
* Tokenization
* Remove special characters
* Remove stopwords
* Stemming using Porter Stemmer
* Feature extraction using TF-IDF Vectorizer

---

## 🤖 Machine Learning Model

### Algorithms Used

* Multinomial Naive Bayes
* TF-IDF Vectorizer

### Workflow

1. Data Cleaning
2. Text Preprocessing
3. Feature Extraction (TF-IDF)
4. Model Training
5. Model Evaluation
6. Model Serialization using Pickle
7. Streamlit Deployment

---

## 📈 Model Performance

Performance Metrics:

* Accuracy Score
* Precision Score
* Confusion Matrix

The trained model achieves high accuracy in distinguishing spam messages from legitimate messages.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* NLTK
* Scikit-Learn
* Streamlit
* Pickle

---

## 📂 Project Structure

```text
SMS-Spam-Detection/
│
├── SPAM_DETECT.ipynb
├── app.py
├── model.pkl
├── vectorizer.pkl
├── README.md
│
└── spam.csv
```

---

## ▶️ Running the Project

### Clone Repository

```bash
git clone https://github.com/your-username/SMS-Spam-Detection.git
cd SMS-Spam-Detection
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Streamlit Application

```bash
streamlit run app.py
```

---

## 📱 Application Workflow

1. Enter an SMS message.
2. Click on Predict.
3. The model processes the message.
4. The application displays:

   * Spam 🚫
   * Ham ✅

---

## 📷 Sample Predictions

| Message                                           | Prediction |
| ------------------------------------------------- | ---------- |
| Congratulations! You won ₹10,000. Click here now! | Spam 🚫    |
| Hey, are we meeting today?                        | Ham ✅      |


---

## 👨‍💻 Author

**Tanudip Ghosh**

If you found this project useful, please consider giving it a ⭐ on GitHub.
