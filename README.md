# Fake-News-Detection-Model
A machine learning system that classifies news articles as fake or real using NLP techniques.

## Dataset
- ISOT Fake News Dataset — 44,689 articles
- 23,478 fake + 21,211 real articles

## Models
- Logistic Regression — 98.62% accuracy
- Random Forest — 99.77% accuracy

## How to Run
1. Clone the repo
2. Install dependencies:
pip install pandas numpy scikit-learn nltk scipy joblib voila ipywidgets
3. Open main.ipynb and run all cells
4. For the demo: voila main.ipynb

## Files
- main.ipynb — main notebook with training and demo widget
- fake_news_model.pkl — saved Random Forest model
- vectorizer.pkl — saved TF-IDF vectorizer
- datasets/ — Fake.csv and True.csv

## Tech Stack
Python · scikit-learn · NLTK · TF-IDF · Jupyter · Voila