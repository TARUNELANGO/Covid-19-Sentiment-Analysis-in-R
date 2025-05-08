# 🦠 Covid-19 Sentiment Analysis in R  
_A classification model to predict the sentiment of Covid-19 tweets using R_

---

## 🎯 Project Objective

- 📈 Gain insights from COVID-19-related textual data.
- 🧠 Perform sentiment and network analysis on the tweets.
- 💬 Visualize primary emotions like **trust**, **fear**, **anticipation**, etc.
- 📊 Create multiple visualizations to better understand user sentiments.
- 🌐 Use **Social Network Analysis** to display relationships among frequently used words via graphs.

---

## 📂 Dataset Source

🔗 [Kaggle Dataset Input](https://www.kaggle.com/code/andradaolteanu/covid-19-sentiment-analysis-social-networks/input)  
📚 Data includes information from Bing, COVID-19 Daily Updates, etc.

---

## 🧪 Methodology

- 📊 Use of **bar charts**, **word clouds**, and other visual tools to depict hidden patterns.
- 🔍 Analyze **positive and negative** keywords to strengthen sentiment prediction.
- 🧹 Apply lexicon-based approach — cleaning using stopwords, punctuation removal, etc.
- 📚 Tokenize text into **unigrams**, **bigrams**, and **trigrams** for efficient processing.

---

## 🧠 Algorithms Used

### 🧾 Rule / Lexicon-Based Approach
- ✅ Relies on dictionaries of **positive** and **negative** words.
- ⚖️ Calculates sentiment scores based on word polarity.
- 🔧 Can be customized using expressions and contextual rules.

### 🔑 Keyword Spotting
- 🔎 Scans text for sentiment-specific keywords like *happy*, *sad*, *disappointed*, etc.
- 🎯 Employs a **keyword recovery algorithm** to reduce noise and false alarms.
- 📈 Detection accuracy improved from **78.1% → 85.3%** at 10% false alarm rate.

---

## ⚙️ Workflow

1. 📥 Import and explore the dataset
2. 🧼 Clean and prepare the textual data
3. ✂️ Remove stopwords, punctuation, and whitespace
4. 🧩 Tokenize text into n-grams
5. 📘 Apply lexicons for sentiment prediction
6. 🎨 Generate word clouds to visualize sentiment and emotion
7. 🔗 Perform **social network analysis** on co-occurring words
8. 📌 Draw conclusions from visual and analytical results

---

## 📊 Key Parameters

| Parameter         | Description                                  |
|-------------------|----------------------------------------------|
| 🦠 Confirm         | Number of confirmed COVID-19 cases            |
| 💚 Recovered       | Number of recovered patients                  |
| ⚰️ Death           | Number of deaths                              |
| 📍 User Location   | User’s location during tweet posting         |
| 📝 Text            | The actual tweet text                         |
| 📅 Date            | Date when tweet was posted                    |
| 👥 User Followers  | Follower count of the user                    |
| ❤️ User Favorites  | Favorites the user had at time of tweet       |
| 🤝 User Friends    | Friend count of the user                      |

---

## 📁 Additional CSVs for Analysis

- 📄 [covid19_tweets.csv](https://drive.google.com/file/d/1UypbFGcjSquTZdMCa9VhYkre6aDCgfdp/view?usp=share_link)  
- 📄 [covid-19-all.csv](https://drive.google.com/file/d/17k-cfBqZUcgecPm5m829LLz3npVddzKw/view?usp=share_link)  
- 📄 [worldcitiespop.csv](https://drive.google.com/file/d/1CvMg2ICE2tB3ZDziCwLaZiGgHJIHszWa/view?usp=share_link)

---
