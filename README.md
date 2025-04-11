# Graph-Based-Financial-Analysis-of-SEC-Filings

This project provides a Python-based notebook to analyze SEC (Securities and Exchange Commission) filings using Natural Language Processing (NLP) and data visualization techniques. The primary goal is to extract meaningful insights from financial documents like 10-Ks and 10-Qs.

---

## 🔍 Features

- Automatically loads and processes SEC filings data.
- Performs text preprocessing (tokenization, stopword removal, etc.).
- Visualizes key trends using word clouds and frequency analysis.
- Computes sentiment scores to gauge the tone of financial documents.
- Supports customizable filters for company, year, and filing type.

---

## 🚀 Getting Started

### Prerequisites

Ensure you have Python 3.7+ installed. Then install the required packages:

```bash
pip install -r requirements.txt
```
You may also need the following libraries if not included:
```bash
pip install pandas matplotlib seaborn nltk wordcloud
```
Running the Notebook
Open the notebook in Jupyter or VSCode:

```bash
jupyter notebook analyze_SEC_filings.ipynb
```
## 🧠 Methodology
Data Ingestion: SEC filings are either pre-downloaded or fetched via EDGAR API (if extended).

Preprocessing: Uses NLTK for cleaning, tokenization, stopword removal, and basic normalization.

Analysis:

Frequency plots of key financial terms

Sentiment analysis using VADER (or TextBlob as an alternative)

Word clouds to visualize dominant terms

Visualization: Matplotlib & Seaborn are used for plots and analysis charts.

## 📌 Use Cases
Detect trends in financial tone over time

Compare sentiment across companies

Identify frequently used financial terms by industry

## ✅ To-Do / Improvements
 Add functionality to fetch SEC filings directly using EDGAR API

 Enhance sentiment analysis with deep learning models (e.g., FinBERT)

 Build Streamlit or Flask UI for non-technical users

 Export insights as reports (PDF, Excel)

## 🙌 Acknowledgments
SEC EDGAR Database

NLTK & WordCloud libraries

Matplotlib, Seaborn, Pandas for data processing and visualization
