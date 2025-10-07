# Fake-Review-Detection-using-AI-and-Machine-Learning
Developed an AI-based fake review detection system using logistic regression, analyzing text data for authenticity

## Project Overview

Online reviews play a crucial role in e-commerce decisions, but fake reviews can mislead users. This system uses **Logistic Regression** to classify reviews as **genuine** or **fake** by analyzing the textual content of the review.

The system includes:

- Text preprocessing using NLP
- Feature extraction using **TF-IDF**
- Model training using Logistic Regression
- Evaluation using accuracy, precision, recall, F1-score, and ROC-AUC
- Predicting on new reviews

---

## Dataset

- **Source:** Kaggle / public datasets  
- **Example:** `fake_reviews_dataset.csv`  
- **Columns:**
  - `review`: The review text
  - `label`: 1 for fake, 0 for genuine  

The dataset is cleaned to remove missing values before training.

---
## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/fake-review-detection.git
cd fake-review-detection
```

2. Install Dependencies
 ```bash
pip install pandas scikit-learn nltk joblib
```
