# Cyberbullying Classifier

Academic NLP classification project for detecting cyberbullying-related text using traditional machine-learning models.

> **Project type:** Academic / learning project

## Pipeline

```text
Raw tweets
   ↓
Text cleaning
   ↓
Tokenization
   ↓
Stop-word removal
   ↓
Lemmatization
   ↓
TF-IDF
   ↓
Stratified train/test split
   ↓
Model comparison
   ↓
Classification metrics
```

## Models explored

- Multinomial Naive Bayes
- Logistic Regression
- Decision Tree
- Random Forest

## Evaluation

The notebook uses:

- Accuracy
- Classification report
- Confusion matrix

The repository does not claim a single benchmark score in the README because the result depends on the exact dataset and execution.

## Repository structure

```text
Cyberbullying-Classifier/
├── README.md
└── requirements.txt
```

## Data

The original notebook expects a dataset named `cyberbullying_tweets.csv`. The dataset itself is not committed here by default.

## Status

Academic NLP/ML work preserved for learning and portfolio context. It should not be interpreted as a production moderation or safety system.

## Author

**Shaik Muneeruddin**
