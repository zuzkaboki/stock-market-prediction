
# Market Direction Prediction Using Machine Learning

## Project Overview

This project explores the relationship between global financial market movements and the daily opening direction of India's Nifty 50 stock market index.

The analysis uses historical financial data from 2019 to 2024 and applies statistical analysis and machine learning classification models to investigate whether previous market movements can help predict the direction of the Nifty 50 index.

The project also includes a sentiment analysis component using VADER to examine the sentiment of a generated Nifty 50-related text corpus.

## Repository Structure

```text
stock-market-prediction/
│
├── data/
│   ├── Master_data_Zuzana.csv
│   └── Twitter_Nifty50_Corpus.txt
│
├── notebooks/
│   ├── market_direction_prediction.ipynb
│   └── sentiment_corpus_generation.ipynb
│
├── presentation/
│   └── Capstone project presentation PPT.pptx 
│
├── README.md
├── requirements.txt
└── .gitignore

## Objectives

- Analyse historical financial market data.
- Explore relationships between global stock market indices.
- Identify patterns influencing Nifty 50 opening movements.
- Develop and compare machine learning classification models.
- Apply sentiment analysis to financial text data.

## Dataset

Historical financial data was collected using Yahoo Finance.

The analysis includes the following market indicators:

- Nifty 50
- Dow Jones Industrial Average
- DAX
- Hang Seng Index
- Nikkei 225
- CBOE Volatility Index (VIX)

Time period: January 2019 – December 2024.

## Methodology

The project includes:

1. Data collection and preparation
2. Exploratory Data Analysis (EDA)
3. Statistical analysis and correlation analysis
4. Feature engineering using lagged daily returns
5. Machine learning model development
6. Model evaluation and comparison
7. Sentiment analysis using VADER
8. Data visualisation and interpretation

## Machine Learning Models

Four classification algorithms were implemented and evaluated:

- Logistic Regression
- Naive Bayes
- Decision Tree
- Random Forest

The models were evaluated using accuracy, ROC curves, AUC scores and confusion matrices.

## Results

Random Forest achieved the highest test AUC of approximately 0.737, outperforming the other tested classification models.

The results indicate moderate predictive discrimination between upward and downward market movements.

The models showed a tendency to predict upward movements more frequently, highlighting class-specific performance limitations.

## Sentiment Analysis

The sentiment analysis component uses VADER (Valence Aware Dictionary and sEntiment Reasoner).

A generated text corpus was used to demonstrate text preprocessing, sentiment classification and visualisation.

The text corpus consists of generated data rather than actual collected Twitter/X posts. Therefore, the sentiment results should not be interpreted as evidence of real-world social media sentiment.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy
- Statsmodels
- NLTK
- VADER

## Project Presentation

[View the project presentation (PPTX)](presentation/Capstone%20project%20presentation%20PPT.pptx)

## Project Limitations

- Historical market relationships do not guarantee future predictive performance.
- The classification models show limitations in identifying downward market movements.
- The sentiment analysis uses generated text data rather than actual social media posts.

## Disclaimer

This project was developed as part of an academic Data Science programme. It is intended for educational and analytical purposes only and does not constitute financial or investment advice.
