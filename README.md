# SMS Spam Detection – Your Inbox's Bodyguard

Do you hate spam texts as much as we do?

This project is your first line of defense against unwanted SMS and email spam. We built a machine learning-powered system that can classify incoming messages as **Spam** or **Not Spam**—and it does it with precision, speed, and a touch of AI magic.

---

## Project Overview

With millions of unwanted messages flooding inboxes daily, spam detection has become essential. This project uses Natural Language Processing (NLP) and supervised machine learning to:

- Understand the patterns and keywords in spam messages
- Train an intelligent model on real-world SMS/email data
- Detect spam in real-time through a web interface

Whether you're curious about NLP or want to see machine learning in action—this project offers a practical, hands-on implementation.

---

## What This Project Does

**Data Cleaning & Preprocessing**  
- Removes noise like punctuation and special characters  
- Tokenizes text using `nltk`  
- Applies stemming to normalize message structure  
- Transforms text into numerical form using TF-IDF

**Exploratory Data Analysis**  
- Analyzes spam vs non-spam distribution  
- Visualizes message length and keyword frequency  
- Identifies patterns specific to spam content

**Model Training & Evaluation**  
- Trains models like **Naive Bayes**, **Logistic Regression**, and optionally **SVM**  
- Evaluates accuracy, precision, recall, F1-score, and confusion matrix  
- Selects the best model based on performance metrics

**Web App for Prediction**  
- Enter your own message in a clean interface  
- See real-time prediction: spam or not spam  
- Built using **Streamlit** or **Flask**

---

## Tech Stack

| Tool/Library     | Purpose                        |
|------------------|--------------------------------|
| Python           | Programming Language           |
| pandas, numpy    | Data manipulation              |
| nltk             | NLP: tokenization, stemming    |
| scikit-learn     | ML models & TF-IDF vectorizer  |
| matplotlib       | Data visualization             |
| Streamlit/Flask  | Web app deployment             |

---

## Results

 -Achieved over 96% accuracy on the test set
 -Balanced precision and recall, reducing both false positives and false negatives
 -Real-time predictions with a friendly web interface
