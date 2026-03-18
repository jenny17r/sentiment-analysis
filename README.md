# IMDB Sentiment Analysis using NLP

## Description

This project performs sentiment analysis on IMDB movie reviews using Natural Language Processing (NLP) techniques and Machine Learning models.
The goal is to classify reviews as positive (1) or negative (0).

---

## Tech Stack

* Python
* NumPy
* Pandas
* NLTK
* Scikit-learn

---

## Dataset

* IMDB Dataset (50,000 movie reviews)
* Each review is labeled as positive or negative

---

## Workflow

### Data Preprocessing

* Sampled 1000 reviews from dataset
* Removed HTML tags
* Removed special characters
* Converted text to lowercase
* Removed stopwords using NLTK
* Applied stemming using PorterStemmer

---

### Feature Engineering

* Used Bag of Words (CountVectorizer)
* Converted text into numerical vectors

---

### Model Building

Trained multiple Naive Bayes models:

* Gaussian Naive Bayes
* Multinomial Naive Bayes
* Bernoulli Naive Bayes

---

### Model Evaluation

* Accuracy Score
* Confusion Matrix

---

## Results

* Multinomial Naive Bayes Accuracy: ~81%
* Bernoulli Naive Bayes Accuracy: ~79%

---

## Installation & Setup

```bash
git clone https://github.com/your-username/imdb-sentiment-analysis.git
cd imdb-sentiment-analysis
pip install -r requirements.txt
jupyter notebook
```

---

## Project Structure

```
├── IMDB Dataset.csv
├── sentiment_analysis.ipynb
├── README.md
```

---

## Key Learnings

* Text preprocessing techniques in NLP
* Feature extraction using Bag of Words
* Comparison of Naive Bayes models
* Model evaluation using accuracy and confusion matrix

---

## Future Improvements

* Use TF-IDF instead of CountVectorizer
* Try advanced models (Logistic Regression, SVM, LSTM)
* Deploy as a web app using Streamlit
* Increase dataset size for better accuracy

---

## Contact

Jayapriya R
GitHub: https://github.com/jenny17r

