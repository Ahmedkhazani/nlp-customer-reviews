# Text Classification using Logistic Regression

This project demonstrates a simple text classification pipeline using Natural Language Processing (NLP) and Logistic Regression. It includes text preprocessing, vectorization using n-grams, and training a classifier to predict categories based on input text.

## 📌 Features

- Exploratory Data Analysis (EDA)
- Text preprocessing using `regex`, `spaCy`, and `NLTK`
- Vectorization with `CountVectorizer`
  - `ngram_range=(1,2)`
  - `max_features=15000`
  - `min_df=2`
- Logistic Regression modeling with `solver='saga'`, `max_iter=200`
- Performance evaluation

## 📁 Project Structure

```
.
├── Untitled24.ipynb        # Main notebook
├── README.md               # Project description
├── requirements.txt        # Python dependencies
```

## 📦 Requirements

Install the dependencies using pip:

```bash
pip install -r requirements.txt
```

## 📊 Model

- Model: `LogisticRegression`
- Features: n-gram (1,2), 15k max features
- Text Cleaning: stopword removal, stemming, POS tagging

## 📄 License

This project is for educational purposes.
