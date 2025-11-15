# NLP Analysis of Social Media Communication  
**By Shervin Zare**

This project uses Natural Language Processing techniques to analyze communication patterns in a real-world Twitter dataset. The analysis explores sentiment trends, text structure, and behavioral patterns across time and device type.

---

## 📊 Dataset  
The primary dataset used in this project is the **Trump Tweet Dataset**, available on Kaggle:  
👉 [Trump Tweet Dataset](https://www.kaggle.com/datasets/rishidamarla/trumps-tweets)

**Overview:**  
This dataset contains thousands of tweets posted by Donald Trump over multiple years. It includes:  
- Tweet text  
- Timestamps  
- Device used (Android / iPhone / Web)  
- Engagement metrics  
- Additional metadata  

This dataset allows for temporal analysis, NLP-based sentiment scoring, device-based behavioral comparisons, and communication pattern exploration.

---

## 🧠 Sentiment Lexicon (VADER)  
Sentiment scoring in this project uses the **VADER Lexicon**, available here:  
👉 [VADER Sentiment Lexicon](https://www.kaggle.com/datasets/nltkdata/vader-lexicon)

**About VADER:**  
VADER (Valence Aware Dictionary and sEntiment Reasoner) is a lexicon and rule-based sentiment analysis tool specifically designed for social media text. It is:  
- Tuned for microblog-style communication  
- Human-validated and empirically tested  
- Excellent for short text, emojis, punctuation emphasis, and slang  

It provides **positive**, **negative**, **neutral**, and **compound** sentiment scores for each tweet.

---

## 🔍 Key Features
- Text cleaning, normalization, and tokenization  
- Sentiment analysis using VADER  
- Hourly and daily communication pattern analysis  
- Device-based behavior comparison  
- Regex-based text pattern extraction  
- High-quality visualizations with Matplotlib & Seaborn  

---

## 🛠️ Tools & Libraries
- Python (Pandas, NumPy)  
- NLTK / VADER  
- Matplotlib, Seaborn  

---

## 📁 Project Structure
- `notebooks/` – main analysis notebook  
- `data/` – cleaned dataset  
- `figures/` – generated plots  

---

## ✨ What This Demonstrates
Practical NLP experience, real-world dataset cleaning, sentiment analysis, regex usage, and time-based communication analytics.

