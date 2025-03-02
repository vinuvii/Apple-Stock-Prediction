# Apple Stock Price Prediction Using Twitter Sentiment Analysis

Predicting Apple's stock price movements using text analytics and sentiment analysis of Twitter data.

## 📌 Project Overview
This project analyzes Apple's stock price trends (2015-2019) using:
- Historical stock data from Yahoo Finance
- Twitter sentiment analysis (3M+ tweets)
- Machine learning models for price prediction
- Trading strategy evaluation

Key Features:
- Text preprocessing pipeline for Twitter data
- Sentiment analysis using VADER and AFINN
- Predictive modeling (Linear Regression, Prophet, Random Forest)
- Profitability analysis of trading strategies

## 🛠 Installation
1. Clone repository:
```bash
git clone https://github.com/yourusername/apple-stock-prediction.git
cd apple-stock-prediction
```

2. Install requirements:
```bash
pip install -r requirements.txt
```

Required Libraries:
```text
pandas==1.3.4
numpy==1.21.4
nltk==3.6.5
scikit-learn==1.0.2
matplotlib==3.5.0
seaborn==0.11.2
prophet==1.0.1
```

## 🚀 Usage
1. **Data Preparation**:
   - Download datasets from [Kaggle Tweets](https://www.kaggle.com/datasets/omermetinn/tweets-about-the-top-companies-from-2015-to-2020) and [Yahoo Finance](https://finance.yahoo.com/quote/AAPL/history)
   - Place in `data/` directory

2. **Run Analysis**:
```python
# Main analysis notebook
jupyter notebook Apple_Stock_Prediction_Analysis.ipynb
```

## 🔍 Data Sources
- **Tweets Data**: [Kaggle Dataset](https://www.kaggle.com/datasets/omermetinn/tweets-about-the-top-companies-from-2015-to-2020)
- **Stock Data**: [Yahoo Finance](https://finance.yahoo.com/quote/AAPL/history)

## 📈 Methodology
1. **Data Preprocessing**:
   - Text cleaning (URLs, emojis, mentions)
   - Tokenization & lemmatization
   - Sentiment scoring (VADER/AFINN)

2. **Exploratory Analysis**:
   - Tweet frequency analysis
   - Stock price correlations
   - Sentiment distribution

3. **Model Building**:
   - Linear Regression (RMSE: 0.87)
   - Prophet Model (R²: 0.98)
   - Random Forest comparison

4. **Trading Strategy**:
   - Position-based trading
   - Profit/Loss analysis
   - Drawdown evaluation

## 📊 Results
Key Findings:
- Sentiment scores show 0.89 correlation with price movements
- Best model: Linear Regression (Lowest RMSE)
- Trading strategy achieved 25.36% cumulative profit

Visualizations:
- Sentiment trends over time
- Word clouds of key terms
- Cumulative profit analysis
- Drawdown evaluation

