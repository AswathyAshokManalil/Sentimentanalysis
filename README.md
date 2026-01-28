# Emotion Analysis using NLP

This project demonstrates **sentiment/emotion classification** from text comments using **Natural Language Processing (NLP)** and **Machine Learning**. The goal is to classify comments into emotions such as **anger, fear, joy**, etc., using both **Naive Bayes** and **Support Vector Machine (SVM)** models.

---

## Project Overview

The workflow of this project includes the following steps:

### 1. Data Loading & Preprocessing
- Converting all text to **lowercase**  
- Removing **URLs, numbers, and special characters**  
- **Tokenization** and **stopword removal**  
- **Text cleaning and normalization**  

### 2. Feature Extraction
- **TF-IDF vectorization** to convert text into numerical features suitable for machine learning  

### 3. Model Training
- **Multinomial Naive Bayes**  
- **Linear Support Vector Machine (SVM)**  

### 4. Model Evaluation
- Comparing **Accuracy** and **F1-score**  
- Selecting the **best-performing model**  

---

## Dataset

The dataset (`nlp_dataset.csv`) contains two columns:

| Comment | Emotion |
|---------|---------|
| i seriously hate one subject to death... | fear |
| im so full of life i feel appalled | anger |

---

## Technologies Used

- **Python 3**  
- **pandas** – Data manipulation  
- **nltk** – Natural Language Toolkit (stopword removal)  
- **scikit-learn** – Machine learning (TF-IDF, NB, SVM, metrics)  
- **Google Colab** – Environment for execution  

---

## Results

| Model | Accuracy | F1-score |
|-------|----------|----------|
| Naive Bayes | 90.82% | 0.908 |
| SVM | 95.29% | 0.953 |

> **Conclusion:** SVM outperformed Naive Bayes and is recommended for emotion classification in this context.  

---

