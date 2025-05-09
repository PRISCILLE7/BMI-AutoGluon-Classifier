# Sentiment Analysis on Financial News Headlines

This repository contains a data science project focused on analyzing sentiment in financial news headlines. The goal is to classify headlines as **positive**, **negative**, or **neutral**, using natural language processing (NLP) and machine learning techniques.

 Dataset: `financial_headlines.csv`  
 Notebook: `sentiment_analysis_finance.ipynb`  
 Domain: Finance + NLP + Text Classification

---

##  Objectives

- Preprocess financial news headlines for NLP tasks.
- Apply sentiment labeling using rule-based or manual annotations.
- Extract features using Bag-of-Words and/or TF-IDF vectorization.
- Train and evaluate machine learning classifiers (Logistic Regression, Naive Bayes, etc.).
- Visualize classification results and key insights.

---

##  Files Included

- `financial_headlines.csv`: CSV file with financial headlines and (optionally) sentiment labels.
- `sentiment_analysis_finance.ipynb`: Jupyter Notebook containing data exploration, preprocessing, model training, and evaluation.
- `README.md`: Project documentation.

---

##  Libraries & Tools

- Python 3
- Pandas
- NumPy
- Scikit-learn
- NLTK / SpaCy (for preprocessing)
- Matplotlib / Seaborn (for visualization)

---

##  Key Steps in the Notebook

1. **Loading the dataset**
2. **Text cleaning and preprocessing**:
   - Lowercasing
   - Removing punctuation/stopwords
   - Tokenization
3. **Exploratory Data Analysis (EDA)**:
   - Word frequency
   - Distribution of sentiment classes
4. **Feature Extraction**:
   - CountVectorizer
   - TF-IDF
5. **Model Training & Evaluation**:
   - Logistic Regression
   - Naive Bayes
   - Accuracy, F1-score, confusion matrix
6. **Insights & Conclusion**

---

##  Results Summary

- Best-performing model: Logistic Regression with TF-IDF features.
- Challenges include handling ambiguous or sarcastic headlines.
- Accuracy and macro F1-score reported in the notebook.

---

##  Author

Priscille Ebwala  
M2 SIM — Vietnam National University (IFI)  
Email: ebwalette@gmail.com

---

##  Educational Use

This project was conducted as part of coursework in Natural Language Processing, and serves as an introduction to applying machine learning for sentiment analysis in finance.