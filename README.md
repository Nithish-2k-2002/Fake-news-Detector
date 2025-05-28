# Fake News Classifier

A simple machine learning project to classify news articles into categories based on their text using Logistic Regression and TF-IDF.

## Dataset
Place the CSV file inside the `dataset/` folder. The dataset should have at least these columns:
- `text`: the full content of the article
- `subject`: the label/category (e.g., fake, real)

## How to Run

```bash
pip install -r requirements.txt
python fake_news_classifier.py
