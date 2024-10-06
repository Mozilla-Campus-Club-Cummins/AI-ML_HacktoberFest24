# Email Spam Classifier

## Overview
This project is a machine learning-based email spam classifier that uses **Logistic Regression** to classify emails as spam or not spam. The model is trained on a dataset of labeled emails and can predict whether a given email is spam or not. The project uses natural language processing (NLP) techniques to preprocess the text data and convert it into features suitable for machine learning algorithms.

## Features
- Preprocessing of email text data, including cleaning, tokenizing, and vectorizing.
- Utilization of **TF-IDF (Term Frequency-Inverse Document Frequency)** for feature extraction.
- Email classification using **Logistic Regression**.
- Performance evaluation of the model using metrics such as accuracy, confusion matrix, and ROC-AUC.
- Visualization of the confusion matrix and ROC curve.
- Classification of new emails as spam or not spam.

## Dataset
Downloaded this dataset from kaggle url: https://www.kaggle.com/datasets/esraaaabdelrazek/mail-data

{reduced the number of rows due to git size limit for commit}
The dataset used is in CSV format, containing two columns:
- **Category**: Labels emails as either `spam` or `ham` (not spam).
- **Message**: The content of the email message.

## Libraries Used
- `numpy`
- `pandas`
- `scikit-learn`
  - `TfidfVectorizer`
  - `LogisticRegression`
  - `train_test_split`
  - `accuracy_score`
- `matplotlib` for plotting the confusion matrix and ROC curve.
- `seaborn` for visualization.

## Model Overview
- **Preprocessing**: Text data is cleaned by removing punctuation and converting to lowercase. Stopwords are removed, and the emails are transformed into numerical feature vectors using `TfidfVectorizer`.
- **Model Training**: The `LogisticRegression` model is trained on 80% of the data, and its performance is evaluated on the remaining 20%.
- **Performance Metrics**: Accuracy, confusion matrix, classification report, and ROC-AUC are used to assess model performance.

## How to Run the Project
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/email-spam-classifier.git
   cd email-spam-classifier

