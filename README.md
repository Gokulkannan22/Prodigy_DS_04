# 🐦 Twitter Sentiment Analysis – EDA (Task 4)

This project is part of my Data Science Internship at **Prodigy InfoTech**.

The task focused on analyzing sentiment patterns in social media data to understand public opinion and attitudes towards specific entities and topics.

---

## 📁 Files Included

- `twitter_training.csv` – Main dataset containing tweets, sentiment, and entities
- `twitter_sentiment.ipynb` – Jupyter notebook with step-by-step EDA and visualizations
- `README.md` – Project documentation
- `screenshots/` – Visual outputs (sentiment distribution and WordClouds)

---

## 📊 Key Steps Performed

### Step 1: Load Dataset  
Loaded the raw Twitter dataset and previewed the structure.

### Step 2: Rename Columns & Handle Nulls  
- Renamed columns for clarity (`ID`, `Entity`, `Sentiment`, `Tweet`)
- Found and dropped rows with missing `Tweet` content

### Step 3: Sentiment Distribution  
- Plotted the count of `Positive`, `Negative`, and `Neutral` tweets

### Step 4: WordClouds by Sentiment  
- Created WordClouds to visualize frequent words used in:
  - Positive tweets
  - Negative tweets
  - Neutral tweets

---

## 💡 Insights

- **Positive tweets** often used playful or brand-focused language  
- **Negative tweets** reflected strong opinion or sarcasm  
- **Neutral tweets** had more factual, emotionless wording  
- Sentiment distribution was imbalanced but informative

---

## 🛠️ Tools Used

- Python
- Jupyter Notebook
- Libraries: `pandas`, `matplotlib`, `seaborn`, `wordcloud`

---

## 📎 Dataset Source

- [Kaggle: Twitter Entity Sentiment Dataset](https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis)

---

## ✅ Outcome

This task enhanced my skills in text data handling, sentiment categorization, and visual storytelling using word clouds and countplots.

---
