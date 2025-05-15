# E-commerce Product Classification Model

## Overview
This project focuses on building a machine learning model to classify e-commerce products into one of the following categories:
- Household
- Electronics
- Clothing & Accessories
- Books

Using natural language processing (NLP) techniques, the model processes product descriptions and predicts the appropriate category with high accuracy.

---

## Features
- **Product Categories**: Categorizes products into one of the four predefined categories.
- **TF-IDF Vectorization**: Converts textual product descriptions into meaningful numerical vectors.
- **Random Forest Classifier**: A robust and interpretable machine learning algorithm.
- **High Accuracy**: Achieved a classification accuracy of **97%**.
- **Evaluation Metrics**: Analyzed model performance using precision, recall, F1-score, and a confusion matrix.

---

## Dataset
The dataset used contains product descriptions and their corresponding categories. The text data was preprocessed and transformed for feature extraction.

---

## Methodology
1. **Data Preprocessing**:
   - Cleaned and tokenized product descriptions.
   - Removed stopwords, applied stemming/lemmatization.

2. **Feature Engineering**:
   - Transformed text data using **TF-IDF Vectorization** to convert textual descriptions into numerical features.

3. **Model Development**:
   - Trained a **Random Forest Classifier** on the transformed features.
   - Tuned hyperparameters for optimal performance.

4. **Evaluation**:
   - Evaluated using a confusion matrix to measure precision, recall, and F1-score across all categories.

---

## Results
- **Accuracy**: 97%
- The model performs exceptionally well across all four categories, ensuring reliable classification of e-commerce products.
