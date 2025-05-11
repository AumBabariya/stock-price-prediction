# Stock Price Movement Prediction using News Sentiment 

This project aims to predict stock price **movement (up/down)** by analyzing historical **Dow Jones Industrial Average (DJIA)** data alongside **news sentiment** from **New York Times headlines**.

I built this project to explore how financial trends are influenced by both **numerical indicators** and **textual sentiment**, using classic machine learning models.

---

## Technologies Used

- Python (Pandas, NumPy)
- Natural Language Processing (NLTK)
- Scikit-learn
- Jupyter Notebook
- Matplotlib / Seaborn

---

## Workflow

1. **Data Collection**  
   - DJIA historical prices from Yahoo Finance  
   - NYT headlines dataset (2008–2016)

2. **Data Preprocessing**  
   - Cleaned and merged both datasets by date  
   - Used NLTK to perform sentiment scoring on headlines

3. **Feature Engineering**  
   - Created sentiment features using VADER  
   - Engineered daily percentage change labels for price

4. **Model Training**  
   - Trained Logistic Regression, SVM, and Random Forest models  
   - Evaluated models using accuracy and confusion matrix

5. **Visualization**  
   - Plotted sentiment trends vs stock movement  
   - Displayed model performance over different time slices

---

## What I Learned

- How to engineer features from both text and time-series data  
- How sentiment can amplify or contradict technical indicators  
- Improved hands-on understanding of classification and preprocessing pipelines

---

## Results

| Model               | Accuracy |
|--------------------|----------|
| Logistic Regression| 59%      |
| Random Forest      | 63%      |
| SVM                | 58%      |

*Best results were obtained using a combination of price features and sentiment polarity.*

---
