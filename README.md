<<<<<<< HEAD
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
=======
# AI-ML_HacktoberFest24

![image](https://github.com/user-attachments/assets/b8a411e6-b2d0-4403-b90b-8fbd5c9cfc9d)

About us :
The Mozilla Campus Club of CCEW was formed to promote the idea of open source among aspiring students and encourage them to make the most of the opportunities that come along with it.

About Repository :
This repository was created specifically to support open-source among college students. As a result, issues might range in severity from easy to challenging.

Instructions for Hacktoberfest:

• You should be a student of CCEW

• One should have registered in Mozilla via the form which was sent and also on the official hacktoberfest website.

• A person throughout this event will be allowed a maximum of 2 PRs.

• Mention your "first name last name" on your GitHub profile (If we are unable to identify you we won't accept your PR).

• Mention your name, your branch, and the year whole requesting to assign the issue.

• Make sure the code has proper comments and indentation

• Any kind of spamming won't be tolerated.

• If any plagiarism is found, the PR will be rejected and no further contribution will be accepted

• Issues will be assigned on a first-come, first-serve basis.

• You will get a maximum of 2 days to work on that issue. If you fail to do so, the issue will be assigned to the next student.

# Contribution Guidelines

Follow the below folder structure 

![image](https://github.com/user-attachments/assets/5b2c28d4-cae8-42ca-a6e8-7d8abaf9039c)

>>>>>>> 3aac3f5f95f494c5d1e800b66d36cc362850a077
