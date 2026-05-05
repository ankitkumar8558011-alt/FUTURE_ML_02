# 🎫 Support Ticket Classification & Prioritization System

## Overview

This project is a Machine Learning-based system designed to automatically classify customer support tickets and assign priority levels.

In real-world scenarios, support teams handle large volumes of tickets daily. This system helps streamline operations by automating ticket categorization and prioritization.

---

## Objectives

The system is built to:

* Read customer support ticket text
* Classify tickets into categories (Billing, Technical Issue, Account, General Query)
* Assign priority levels (High, Medium, Low)
* Improve efficiency in support operations

---

## Tech Stack

* Python
* Scikit-learn
* Pandas
* NumPy
* NLP techniques (text preprocessing, TF-IDF)
* spaCy (for lemmatization)

---

## Features

* Text cleaning (lowercasing, punctuation removal)
* Stopword removal
* Lemmatization using spaCy
* Feature extraction using TF-IDF
* Multi-class classification of tickets
* Priority prediction system
* Model evaluation using:

  * Accuracy
  * Precision
  * Recall
  * F1-score
* Confusion matrix analysis

---

## Machine Learning Models Used

* Logistic Regression (Final Model)
* Naive Bayes (Baseline)
* Random Forest (Comparison)

---

## Project Structure

```id="kz9r2c"
project/
│── data/
│── notebook/
│── model.pkl
│── vectorizer.pkl
│── label_encoder_ticket.pkl
│── label_encoder_priority.pkl
│── README.md
```

---

## How It Works

1. Raw ticket text is cleaned and preprocessed
2. Lemmatization is applied to normalize words
3. Text is converted into numerical features using TF-IDF
4. Machine learning models classify:

   * Ticket Category
   * Ticket Priority
5. Predictions help optimize support workflows

---

## Example

**Input:**

```id="8l9b3y"
My payment failed and money got deducted
```

**Output:**

```id="dxn7jw"
Category: Billing  
Priority: High
```

---

## Model Performance

* Evaluated using classification metrics (accuracy, precision, recall, F1-score)
* Confusion matrix used for detailed performance analysis

(Add your actual accuracy here if available)

---

## Business Impact

* Reduces manual effort in ticket sorting
* Speeds up response time for urgent issues
* Improves customer satisfaction
* Helps teams focus on critical problems

---

## Learning Outcomes

* Hands-on experience with Natural Language Processing
* Building end-to-end machine learning pipeline
* Working with real-world text data
* Model evaluation and comparison

---

## Task-Based Professional Updates

After completing this project, you are encouraged to share a professional update on LinkedIn.

Your post should include:

* A brief overview of what you built (feature, module, or application)
* Key technical learnings or challenges you solved
* Screenshots or outputs demonstrating the workflow
* Project link (GitHub repository)
* Optional: A short demo video or screen recording to showcase functionality

Tag and follow Future Interns to build your professional network.

---

## Future Improvements

* Improve model accuracy with advanced NLP techniques
* Use deep learning models (LSTM, BERT)
* Expand dataset for better generalization
