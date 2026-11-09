# SMS-Spam-Detection
SMS MESSAGE CLASSIFICATION USING ML
# SMS Spam Detection using Machine Learning

A Machine Learning project designed to classify incoming SMS messages as either **Spam** or **Ham** (legitimate messages) using Natural Language Processing (NLP) techniques and classification algorithms.

---

## 📌 Project Overview

With the rise of automated text messaging, spam messages have become a common nuisance and security risk. This project builds an automated text classification pipeline to detect spam messages accurately. It pre-processes textual data, extracts meaningful features using TF-IDF vectorization, and trains a predictive model to identify spam.

---

## 🚀 Features

* **Text Preprocessing:** Cleans raw text data by removing punctuation, special characters, stopwords, and applying stemming/lemmatization.
* **Feature Extraction:** Converts textual input into numerical features using **TF-IDF (Term Frequency-Inverse Document Frequency)**.
* **Model Training:** Utilizes Machine Learning classification models (e.g., Naive Bayes, Logistic Regression, Support Vector Machines).
* **Evaluation Metrics:** Evaluates performance using Accuracy, Precision, Recall, and F1-Score to minimize false positives (marking legitimate messages as spam).

---

## 🛠️ Tech Stack & Libraries

* **Language:** Python 3.x
* **Data Processing & Analysis:** `pandas`, `numpy`
* **Natural Language Processing (NLP):** `nltk` or `spacy`, `re`
* **Machine Learning:** `scikit-learn`
* **Data Visualization:** `matplotlib`, `seaborn`

---

## 📂 Repository Structure

```text
├── dataset/             # Raw and processed datasets (e.g., spam.csv)
├── notebooks/           # Jupyter notebooks for EDA and model training
├── src/                 # Source code files
│   ├── preprocess.py   # Data cleaning and tokenization
│   ├── train.py        # Model training logic
│   └── predict.py      # Inference script for testing new messages
├── README.md            # Project documentation
└── requirements.txt     # Python dependencies
