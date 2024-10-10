# Sentiment Analysis of Movie Reviews

## Overview
This project presents a sentiment analysis of movie reviews using the IMDb movie reviews dataset from the NLTK corpus. The goal is to classify reviews into positive and negative sentiments employing machine learning techniques, specifically Logistic Regression and Support Vector Machine (SVM).

## Contents
- `report.md`: The main report document detailing the analysis and results.
- `data/`: Directory containing the IMDb movie reviews dataset (if applicable).
- `src/`: Directory containing Python scripts for data preprocessing, model training, and evaluation (if applicable).

## Dataset
The analysis utilizes the **IMDb movie reviews dataset**, consisting of 2,000 reviews (1,000 positive and 1,000 negative). Each review is labeled as 'pos' for positive or 'neg' for negative sentiment.

## Methodology
1. **Data Preparation:**
   - Loaded the dataset and preprocessed the reviews by converting text to lowercase, removing stopwords, and applying TF-IDF for feature extraction.

2. **Model Training:**
   - Split the dataset into training (80%) and testing (20%) sets.
   - Trained two models:
     - **Logistic Regression**
     - **Support Vector Machine (SVM)**

3. **Evaluation Metrics:**
   - Assessed model performance using accuracy, precision, recall, and F1-score.

## Implementation

### Data Preprocessing
Key preprocessing steps included stopword removal and TF-IDF vectorization to represent the significance of words in the reviews.

### Model Training and Evaluation
1. **Logistic Regression Model**
   - Achieved an accuracy of **83.75%** with a balanced classification report.
   
2. **Support Vector Machine (SVM) Model**
   - Achieved an accuracy of **82.25%** with slightly lower performance compared to Logistic Regression.

## Results and Discussion
Both models performed well, with Logistic Regression slightly outperforming SVM. Future work may include further preprocessing, hyperparameter tuning, and exploring advanced models to enhance sentiment classification.

## Getting Started
To reproduce the analysis, follow these steps:

1. Clone or download this repository.
2. Install the required libraries:
   ```bash
   pip install nltk scikit-learn
