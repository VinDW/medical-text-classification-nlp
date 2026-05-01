# Medical Text Classification with NLP Report

## 1. Project Overview

This project develops a Natural Language Processing and Machine Learning workflow for classifying healthcare-related text into predefined service categories.

The project is designed as a portfolio demonstration of how unstructured medical or customer-health messages can be transformed into structured categories that support healthcare service routing, customer support, and operational decision-making.

## 2. Business Problem

Healthcare and medical aid organisations receive customer messages relating to symptoms, medication, claims, benefits, chronic care, and emergency situations. Manually reviewing and routing these messages can be time-consuming and may delay service delivery.

A medical text classification model can help identify the type of support required and route each message to the appropriate service area.

## 3. Data

The dataset used in this project is synthetically generated for portfolio and demonstration purposes. It contains short healthcare-related text examples grouped into six categories:

- Symptoms enquiry
- Medication enquiry
- Chronic care enquiry
- Medical aid benefits
- Claims enquiry
- Emergency guidance

No real patient records, confidential clinical information, or private healthcare data are used.

## 4. Methodology

The project follows a standard Natural Language Processing workflow:

1. Create a structured synthetic healthcare text dataset
2. Clean and preprocess text data
3. Perform exploratory text analysis
4. Convert text into numerical features using TF-IDF
5. Train supervised machine learning models
6. Compare model performance
7. Save the best-performing model for reuse

## 5. Models

The following models were trained and compared:

- Logistic Regression
- Multinomial Naive Bayes
- Support Vector Machine

All models used TF-IDF text features extracted from the cleaned healthcare-related text.

## 6. Evaluation

The models were evaluated using:

- Test accuracy
- Cross-validation accuracy
- Precision
- Recall
- F1-score
- Classification report

Because the dataset is synthetic and relatively small, the results should be interpreted as a demonstration of the NLP workflow rather than a production-grade healthcare model.

## 7. Business Value

This project shows how NLP can support healthcare and medical aid organisations by:

- Automatically routing healthcare-related messages
- Reducing manual classification workload
- Improving response times
- Identifying common service categories
- Supporting chatbot and digital service automation
- Creating structured insights from unstructured healthcare text

## 8. Conclusion

This project demonstrates a complete end-to-end healthcare-focused NLP workflow, from data creation and preprocessing to exploratory text analysis, model training, evaluation, and model saving.

It provides practical evidence of skills in Python, Natural Language Processing, supervised machine learning, model evaluation, healthcare text analytics, and business communication.
