# IBM Stock Sentiment & Price Movement Analysis

This project analyzes historical IBM stock data using pandas and matplotlib. It includes sentiment interpretation based on daily movement and visualizes trends over time.

 Dataset: `IBM.csv`  
 Notebook: `ibm_sentiment_analysis.ipynb`  
 Domain: Finance + Data Analysis + Time Series

---

## Objective

To perform basic data cleaning, feature engineering, and visualization of **IBM’s stock price** and derived sentiment (positive, negative, neutral) based on **daily price variation**.

---

##  What's Implemented

- Load and explore a real-world IBM dataset
- Handle missing values and standardize column names
- Compute a new `variation` column (close - open)
- Label sentiment:
  - **Positive**: variation > 0
  - **Negative**: variation < 0
  - **Neutral**: variation = 0
- Plot sentiment distribution over time

---

##  Example Outputs

- Bar chart of positive/negative/neutral days
- Line plots showing stock trends
- Sentiment evolution across the time period

---

##  Libraries Used

- Python 3
- Pandas
- Matplotlib
- Numpy
- seaborn 

---

##  Author

Priscille Ebwala  
Master 2 — Vietnam National University (IFI)  
Email: ebwalette@gmail.com

---

This notebook is intended as a practical introduction to time-series sentiment labeling using financial stock data (IBM case study).
