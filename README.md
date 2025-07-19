# IMDB Movie Review Sentiment Analysis 🎬📊

This project analyzes the sentiment of movie reviews using NLP and machine learning techniques.

## 📌 Project Objective
Classify IMDB movie reviews as positive or negative by applying NLP preprocessing and a logistic regression model.

## 🧠 Technologies Used
- Python
- Pandas, Numpy
- NLTK (Natural Language Toolkit)
- Scikit-learn
- Matplotlib / Seaborn (for visualization)

## ⚙️ Workflow
1. Loaded IMDB dataset from Kaggle
2. Preprocessed the reviews:
   - Removed HTML tags, special characters, and stopwords
   - Tokenized and lemmatized the text
3. Converted text to numerical form using TF-IDF
4. Built a sentiment classification model using Logistic Regression
5. Evaluated using accuracy score and classification report

## 📈 Results
- **Accuracy Achieved:** ~87%
- Learned how text preprocessing dramatically affects model performance.

## 📂 Dataset
[🔗 IMDB Dataset on Kaggle](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)

---


## 🚀 How to Run

1. Clone this repository
2. Download the dataset from Kaggle and place it inside a `data/` folder
3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
4. Open and run the notebook:
IMDb_Sentiment_Analysis.ipynb
