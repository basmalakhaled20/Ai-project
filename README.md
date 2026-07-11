# Spam Email Classifier

A Machine Learning project for detecting spam emails using Natural Language Processing (NLP).

The project preprocesses email text, extracts features using TF-IDF Vectorization, trains a Naive Bayes classifier, and predicts whether an email is Spam or Ham through a simple deployment pipeline.

---

## Features

- Email text preprocessing
- Text cleaning
- TF-IDF Vectorization
- Naive Bayes Classification
- Model serialization using Pickle
- Spam/Ham prediction
- Ready for deployment

---

## Dataset

The dataset contains labeled email messages.

Target classes:

- Spam
- Ham

---

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Pickle
- Jupyter Notebook

---

## Machine Learning Pipeline

1. Load Dataset
2. Clean Text
3. Remove Stopwords
4. TF-IDF Vectorization
5. Train/Test Split
6. Train Naive Bayes Model
7. Evaluate Model
8. Save Model
9. Predict New Emails

---

## Project Structure

```
spam-email-classifier
│
├── dataset
├── models
├── notebooks
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Installation

```bash
pip install -r requirements.txt
```

---

## Run

Open the notebook:

```
notebooks/project_deployment.ipynb
```

---

## Author

Basmala Khaled