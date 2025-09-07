📘 Social Media Sentiment Analysis
📌 Project Overview

This project analyzes social media posts to understand public sentiment on different topics such as iPhone, Cricket, Movies, Traffic, and Festivals.
Using Natural Language Processing (NLP) techniques, the posts are cleaned, preprocessed, and classified into Positive, Negative, or Neutral sentiments.
Visualizations such as sentiment distribution, trends over time, word clouds, and topic-wise analysis are included.

🚀 Features

Preprocessing of noisy social media text (stopword removal, tokenization, lemmatization).

Sentiment classification using TextBlob and VADER.

Graphs:

Sentiment distribution (Bar/Pie chart)

Sentiment trend over time (Line chart)

Word clouds (Positive & Negative)

Topic-wise sentiment (Stacked Bar chart)

Insights highlighting key positive and negative topics.

📂 Project Structure
sentiment-analysis/
│── data/                # dataset (raw & processed)
│── notebooks/           # Jupyter notebooks

│── reports/             # final PDF/Word reports

│── README.md            # project overview

⚙️ Installation & Setup

Clone this repository:

git clone https://github.com/AmitGondJi/sentiment-analysis.git
cd sentiment-analysis


Install dependencies:

pip install -r requirements.txt


Run the Jupyter notebook:

jupyter notebook notebooks/01_sentiment_analysis.ipynb

📊 Visualizations

📌 Example outputs (replace with your figures):

Sentiment Distribution

Trend Over Time

Positive vs Negative Word Clouds

Topic-wise Sentiment Analysis

📈 Results & Insights

Majority of tweets were Positive, followed by Negative and Neutral.

Topics like Festivals and Movies had mostly positive opinions.

Topics like Traffic and Laptop performance had higher negative sentiments.

Word clouds confirmed that positive posts used words like love, amazing, great, while negative posts included worst, frustrated, slow.

🛠️ Tools & Libraries

Python, Pandas, NumPy

NLTK, TextBlob, VADER

Matplotlib, Seaborn

WordCloud
