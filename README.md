
# 🐦 Twitter Sentiment Analysis Project

This project performs sentiment analysis on tweets using Natural Language Processing (NLP) techniques. It can analyze either a sample dataset or real-time tweets from Twitter based on specific keywords.

## 🔍 Features

- Clean and preprocess tweet text
- Analyze sentiment using TextBlob (Positive, Negative, Neutral)
- Visualize sentiment distribution using Seaborn & Matplotlib
- Optional: Fetch real-time tweets using Twitter API v2

## 📁 Files

- `twitter_sentiment_analysis.ipynb`: Jupyter notebook containing the complete analysis pipeline with outputs.
- `README.md`: Project documentation.

## 📦 Libraries Used

- pandas
- matplotlib
- seaborn
- textblob
- tweepy (for real-time Twitter API access)

## 📡 Setup for Real-time Tweet Analysis

1. Create a Twitter Developer account at [developer.twitter.com](https://developer.twitter.com/).
2. Create an App and get your **Bearer Token**.
3. Replace the placeholder in the notebook with your actual Bearer Token.
4. Run the notebook cells to fetch live tweets based on a keyword.

## 🧪 Example Tweets Used (if Twitter API not available)

- "I love the new features of the iPhone!"
- "This is the worst movie I have ever seen."
- "I am feeling okay today."

## 📊 Output

- A table with cleaned tweets and sentiment labels
- A bar plot showing sentiment distribution

## 🚀 How to Run

```bash
pip install -r requirements.txt
jupyter notebook twitter_sentiment_analysis.ipynb
```

## 🤖 Author

Built using Python and NLP techniques for analyzing tweet sentiments. Extendable to any topic with real-time tweet fetching.

