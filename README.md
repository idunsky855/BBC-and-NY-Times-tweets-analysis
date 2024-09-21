# Twitter Data Analysis Project

## Overview
This project analyzes tweets from the official accounts of BBC and The New York Times. Due to recent changes in the Twitter (now X) API and pricing structure, we collected 850 tweets from each account using alternative methods. The project includes data collection, preprocessing, exploratory data analysis (EDA), and various natural language processing (NLP) techniques.

## Data Collection
- Data sources: BBC and The New York Times official Twitter accounts
- 850 tweets collected from each account
- Data saved in CSV files: `bbc_tweets.csv` and `nytimes_tweets.csv`

## Features
1. **Data Preprocessing**
   - Tokenization
   - Lemmatization

2. **Text Analysis**
   - TF-IDF (Term Frequency-Inverse Document Frequency)
   - Word2Vec
   - AutoEncoder for significance extraction

3. **Named Entity Recognition (NER)**

4. **Exploratory Data Analysis (EDA)**
   - Hourly and daily activity patterns
   - Engagement metrics (tweets, likes, posts)

5. **Sentiment Analysis**

6. **Text Summarization**
   - Using pre-trained model `sshleifer/distilbart-xsum-12-1`

7. **Text Completion**
   - Fine-tuned GPT-2 model

## Key Findings
- Distinct daily and hourly patterns in social media activity for both news organizations
- Significant differences in sentiment between BBC (more negative) and NYT (more balanced) tweets
- Variations in engagement metrics across different days of the week

## Technologies Used
- Python
- Libraries: ntscrape, pandas, numpy, matplotlib, seaborn, nltk, gensim, sklearn, transformers, torch

## Setup and Usage
1. Clone the repository
2. Install required dependencies: `pip install -r requirements.txt`
3. Run the Jupyter notebook or Python scripts to reproduce the analysis

## Future Work
- Incorporate real-time data collection using official APIs when available
- Expand analysis to include more news organizations
- Develop a dashboard for real-time sentiment and engagement tracking

## Contributors
Idan Dunsky
Yaniv Kaveh-Shtul
