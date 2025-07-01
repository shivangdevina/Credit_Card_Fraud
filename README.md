# 📈 Netflix Stock Prediction Using Twitter Sentiment Analysis

**Netflix Stock Prediction Using Twitter Sentiment Analysis** is a **Python-based data science project** that combines **natural language processing (NLP)** and **machine learning (ML)** to analyze how Twitter sentiment may influence **Netflix’s stock price trends**.

This project scrapes tweets, performs sentiment analysis, merges the results with historical stock data, and uses predictive models to forecast future stock movements.

---

## 🚀 Features

- **Tweet Scraping:** Collects real-time or historical tweets about Netflix using Twitter API or `snscrape`.
- **Sentiment Analysis:** Analyzes tweet sentiment using tools like **TextBlob** or **VADER**.
- **Data Integration:** Merges sentiment scores with historical stock data.
- **Machine Learning Models:** Trains regression or time series models to predict stock price movements.
- **Visualization:** Plots sentiment trends, stock prices, and prediction results for easy analysis.
- **Performance Metrics:** Evaluates model accuracy using metrics such as **RMSE** and **R²**.

---

## 🛠️ Tech Stack

### 📊 Data & Analysis

- **Python 3.x**
- `pandas`, `numpy` — Data manipulation
- `matplotlib`, `seaborn` — Visualizations
- `tweepy` or `snscrape` — Twitter data collection
- `TextBlob`, `VADER` — Sentiment scoring
- `scikit-learn` — Machine learning models
- `yfinance` — Stock price data

### 🗂️ Storage

- **CSV files** for saving tweets and stock data
- Local storage for plots and model outputs

### 🧪 Environment

- **Jupyter Notebook** for development and experimentation

---

## ✅ Prerequisites

Before you begin, make sure you have:

- **Python 3.8 or higher**
- **pip** for installing dependencies
- **API keys** if using the Twitter API (or use `snscrape` if you prefer no authentication)
- Basic knowledge of running **Jupyter Notebooks**

---

## ⚙️ Setup Instructions

1️⃣ **Clone the Repository**

```bash
git clone <repository-url>
cd netflix-stock-sentiment
