# IMDb Sentiment Analysis

This project performs binary sentiment classification
(positive / negative) on IMDb movie reviews.

The goal is to understand the basic NLP pipeline
using classical machine learning techniques.

---

## Dataset

IMDb Movie Review Dataset (50,000 reviews)
Source: Kaggle

Each review is labeled as:
- positive
- negative

---

## Approach

1. Text preprocessing
2. TF-IDF vectorization
3. Train-test split
4. Multinomial Naive Bayes classifier
5. Model evaluation using accuracy and confusion matrix

---

## Model Used

- TF-IDF Vectorizer
- Multinomial Naive Bayes

---

## Results

The model achieves around 88–91% accuracy
on the test dataset.

---

## Limitations

- The model uses a bag-of-words approach
- It does not fully capture negation
  (e.g. "not amazing")

---

## Possible Improvements

- Use n-grams to handle negation
- Try contextual models like BERT
