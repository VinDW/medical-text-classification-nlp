# Medical Text Classification with NLP

## Overview

This project applies Natural Language Processing and Machine Learning techniques to classify healthcare-related text into service-relevant categories.

The project demonstrates how unstructured medical or customer-health messages can be transformed into structured categories that support healthcare service routing, customer support, and operational decision-making.

The dataset used in this project is synthetically generated for portfolio and demonstration purposes. No real patient records or confidential medical information are used.

## Business Problem

Healthcare and medical aid organisations receive large volumes of customer messages relating to symptoms, medication, claims, benefits, chronic care, and urgent health concerns. Manually reviewing and routing these messages can be time-consuming and may delay service delivery.

This project demonstrates how NLP can be used to classify healthcare-related text into predefined categories, helping organisations route messages more efficiently and identify the type of support required.

## Text Categories

The text examples are classified into the following categories:

- Symptoms enquiry
- Medication enquiry
- Chronic care enquiry
- Medical aid benefits
- Claims enquiry
- Emergency guidance

## Objectives

The objectives of this project are to:

- Create a synthetic healthcare text classification dataset
- Clean and preprocess text data
- Perform exploratory text analysis
- Build supervised machine learning models for text classification
- Evaluate model performance using classification metrics
- Save the best-performing model for future use
- Communicate results in a clear business-focused manner

## Methods

The project uses the following methods:

- Text preprocessing
- Exploratory text analysis
- TF-IDF vectorisation
- Logistic Regression
- Multinomial Naive Bayes
- Support Vector Machine
- Model comparison and evaluation

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib
- Jupyter Notebook
- GitHub

## Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix
- Cross-validation accuracy

## Repository Navigation

- [Project Report](report.md)
- [Data Folder](data/)
- [Notebooks Folder](notebooks/)
- [Outputs Folder](outputs/)
- [Models Folder](models/)
- [Requirements File](requirements.txt)

### Main Notebooks

- [01 Data Creation and Cleaning](notebooks/01_data_creation_and_cleaning.ipynb)
- [02 Exploratory Text Analysis](notebooks/02_exploratory_text_analysis.ipynb)
- [03 Model Training](notebooks/03_model_training.ipynb)

### Key Outputs

- [EDA Summary by Category](outputs/tables/eda_summary_by_category.csv)
- [Top 20 Common Words](outputs/tables/top_20_common_words.csv)
- [Model Comparison Results](outputs/tables/model_comparison_results.csv)
- [Example Predictions](outputs/tables/example_predictions.csv)
- [Category Distribution Plot](outputs/figures/category_distribution.png)
- [Saved Medical Text Classifier](models/best_medical_text_classifier.pkl)
  
## Project Structure

```text
medical-text-classification-nlp/
│
├── README.md
├── data/
│   └── medical_text_data.csv
│
├── notebooks/
│   ├── 01_data_creation_and_cleaning.ipynb
│   ├── 02_exploratory_text_analysis.ipynb
│   └── 03_model_training.ipynb
│
├── outputs/
│   ├── figures/
│   └── tables/
│
├── models/
│   └── best_medical_text_classifier.pkl
│
├── requirements.txt
└── report.md
