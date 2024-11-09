📧 Spam Classification System for Emails and SMS Messages
🎯 Project Overview
This project aims to build a Spam Classification System for identifying unwanted promotional content in emails and SMS messages. The system leverages machine learning algorithms to differentiate between spam and non-spam (ham) messages, providing an effective solution to manage unwanted communications.
The project was deployed using Streamlit for a seamless and interactive user experience.

📊 Dataset
The dataset used in this project is sourced from the UCI Machine Learning Repository[https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset], containing labeled SMS messages as spam or ham. It consists of:

5,574 messages in total
747 spam messages
4,827 non-spam (ham) messages

📊 Exploratory Data Analysis (EDA)
The EDA phase included:

Data Cleaning: Removing missing values and standardizing text.
Visualization: Analyzing the distribution of spam vs non-spam messages.
Text Analysis: Visualizing word frequency using word clouds and bar charts for both spam and ham messages.
Key insights:

Spam messages often contain words like "free", "win", "winner", and "urgent".
Non-spam messages are generally more diverse in language and content.
🤖 Model Building
The following machine learning algorithms were implemented and evaluated:

Naive Bayes Classifier: Achieved high accuracy with a focus on performance.
Logistic Regression: Used as a baseline for comparison.
Support Vector Machine (SVM): Tested for additional performance gains.
The Naive Bayes Classifier performed the best, leveraging its strength in text data classification. It was chosen as the final model for deployment.

🚀 Deployment
The final spam classification model was deployed using Streamlit, providing a simple and interactive user interface. The app allows users to input email or SMS text and classify it as spam or ham in real-time.

