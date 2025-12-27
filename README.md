Name: KAVIYA

Company: COOTECH IT SOLUTIONS
ID: CT04DR2957
Domain: Machine Learning
Duration: DEC 2025 – JAN 2026
Mentor: MUZAMMIL

Overview of the Project-SENTIMENT
ANALYSIS WITH
NLP
![Screenshoot](https://github.com/kaviyaanandan/CODETECH-TASK2/blob/879541b267f35c30e98165558bd67e6ef11e17f4/task-2.png)

Sentiment Analysis with NLP using TF-IDF and Logistic Regression

Objective

The objective of this project is to perform Sentiment Analysis on customer review data using Natural Language Processing (NLP) techniques. The project focuses on transforming textual data into numerical features using TF-IDF Vectorization and building a Logistic Regression classifier to predict sentiment categories such as positive, negative, and neutral.

This project helps in understanding text preprocessing, feature extraction, supervised text classification, and model evaluation, which are essential concepts in NLP-based machine learning applications.

Key Activities
· Data Collection and Creation

A dataset of customer reviews is created containing textual feedback and corresponding sentiment labels (positive, negative, neutral). This serves as the input for the sentiment classification task.

· Data Preprocessing

Textual data is cleaned and prepared for machine learning by:

Encoding sentiment labels into numerical form using LabelEncoder

Handling text data appropriately for NLP models

This step ensures the dataset is compatible with machine learning algorithms.

· Dataset Splitting

The dataset is divided into training and testing sets using train_test_split() to evaluate the model’s performance on unseen data and reduce overfitting.

· Feature Extraction (TF-IDF Vectorization)

Text reviews are converted into numerical feature vectors using TF-IDF Vectorizer, which:

Assigns importance to words based on frequency

Reduces the influence of common stop words

Captures meaningful textual patterns for classification

· Model Building

A Logistic Regression classifier is implemented and trained using the TF-IDF transformed training data. Logistic Regression is chosen due to its efficiency and strong performance in text classification problems.

· Model Evaluation

The trained model is evaluated using:

Classification Report

Model predictions on test data

This helps assess accuracy, precision, recall, and overall sentiment classification performance.
