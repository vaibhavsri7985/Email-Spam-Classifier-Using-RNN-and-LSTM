📧 Spam vs Non-Spam Email Classification
📌 Problem Statement

With the growth of digital communication, spam emails have become a major issue, ranging from unwanted advertisements to malicious phishing attempts. Traditional rule-based filters often fail to capture the evolving patterns of spam.

The objective of this project is to build an intelligent text classification system that automatically distinguishes between Spam and Non-Spam (Ham) emails.

🚀 Project Overview

Implemented Recurrent Neural Network (RNN) and Long Short-Term Memory (LSTM) models.

Used TensorFlow/Keras for deep learning implementation.

Dataset: 190k Spam/Ham Email Dataset from Kaggle.

Evaluation: Compared performance of RNN vs LSTM models.

📂 Dataset

Source: Kaggle - https://www.kaggle.com/datasets/meruvulikith/190k-spam-ham-email-dataset-for-classification

File used: spam_Emails_data.csv

Size: ~190,000 email messages

⚙️ Tech Stack:-

Python

Pandas, NumPy – Data Handling

Matplotlib, Seaborn – Visualization

TensorFlow/Keras – Model Building

🔑 Key Steps:-

Data Preprocessing

Removed unnecessary characters, punctuation, and stopwords.

Converted text into sequences for model input.

Model Building

Trained both RNN and LSTM models.

Compared accuracy, loss curves, and predictions.

Results

RNN: Lower performance, higher loss.

LSTM: Achieved better accuracy and lower loss.(Training Accurcay LSTM:- 98%+, Validation Accuracy:-95%+, Test Accuracy:- 97%+)

Model correctly classified unseen spam and non-spam examples.

LSTM outperformed RNN in both accuracy and loss reduction.

Example predictions show correct classification of spam and ham emails.
