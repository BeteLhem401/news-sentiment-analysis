# News Sentiment Analysis

## Project Overview

This project analyzes the relationship between financial news headlines and stock market behavior.

The analysis includes:

* Exploratory Data Analysis (EDA)
* Financial news trend analysis
* Publisher analysis
* Keyword extraction from headlines
* Technical indicator analysis
* Sentiment analysis
* Correlation analysis between sentiment and stock returns

Dataset used:

* Financial News Dataset
* Historical Stock Price Dataset

---

# Project Structure

```text
news-sentiment-analysis/
│
├── data/
│   └── raw/
│       ├── raw_analyst_ratings.csv
│       ├── AAPL.csv
│       ├── AMZN.csv
│       ├── GOOG.csv
│       ├── META.csv
│       └── NVDA.csv
│
├── notebooks/
│   └── task1_eda.ipynb
│
├── src/
├── scripts/
├── tests/
├── requirements.txt
├── README.md
└── .gitignore
```

---

# Environment Setup

## Create Virtual Environment

```bash
python -m venv .venv
```

## Activate Environment

### Windows

```bash
.venv\Scripts\activate
```

---

# Install Required Libraries

```bash
pip install pandas matplotlib seaborn scikit-learn nltk wordcloud
```

## Save Dependencies

```bash
pip freeze > requirements.txt
```

---

# Important Note About scikit-learn

If you get this error:

```text
The 'sklearn' PyPI package is deprecated
```

Use this command instead:

```bash
pip install scikit-learn
```

NOT:

```bash
pip install sklearn
```

---

# Task 1: Exploratory Data Analysis

The following analyses were completed:

## Descriptive Statistics

* Dataset shape
* Missing value analysis
* Headline length statistics

## Publisher Analysis

* Top publishers by article count
* Publisher activity visualization

## Stock Analysis

* Most mentioned stocks
* Article distribution per stock

## Time Series Analysis

* Daily publication volume
* News frequency trends over time

## Keyword Analysis

* Common headline keywords using CountVectorizer

---

# Sample Visualizations

The notebook includes:

* Headline length distribution
* Top publishers chart
* Top stocks chart
* Daily news publication trend
* Most common keywords chart

---

# Technologies Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook
* Git & GitHub

---

# Author

Betelhem Hailu
