## Mental Health Text Classification

### Overview

This project uses Natural Language Processing (NLP) and machine learning to classify text into four mental health-related categories: Anxiety, Depression, Normal, and Suicidal.

### Objective

The objective of this project is to preprocess text data, extract useful features using TF-IDF, train different machine learning classification models, and evaluate their performance.

### Dataset

The project uses the **Mental_combined Dataset** obtained from Kaggle.

The dataset contains 992 text records across four categories:

- Anxiety
- Depression
- Normal
- Suicidal

### Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLTK
- Scikit-learn
- XGBoost
- Jupyter Notebook
- Joblib

### Text Preprocessing

The text data was processed using:

- Lowercase conversion
- Punctuation and special-character removal
- Tokenization
- Stopword removal
- Lemmatization

### Feature Extraction

**TF-IDF (Term Frequency-Inverse Document Frequency)** was used to convert the processed text into numerical features for machine learning.

### Machine Learning Models

The following models were trained and evaluated:

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- XGBoost

### Model Evaluation

The models were evaluated using accuracy, classification reports, and confusion matrices.

| Model | Accuracy |
|---|---:|
| Logistic Regression | 64.32% |
| Decision Tree | 53.27% |
| Random Forest | 63.82% |
| SVM | 64.82% |
| XGBoost | 63.32% |

### Project Workflow

```text
Dataset
   ↓
Text Preprocessing
   ↓
TF-IDF Feature Extraction
   ↓
Train-Test Split
   ↓
Machine Learning Models
   ↓
Model Evaluation
   ↓
Prediction
