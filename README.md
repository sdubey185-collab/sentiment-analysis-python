# 🌈 Customer Review Sentiment Analysis & Word Cloud using Python

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.0-blue?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-purple?logo=pandas" />
  <img src="https://img.shields.io/badge/TextBlob-NLP-orange" />
  <img src="https://img.shields.io/badge/Matplotlib-Visualization-green" />
</p>

---

## 🔍 Project Overview

Customer reviews provide valuable insights into product quality and service experiences.

In this project, I used Python to analyse customer feedback and classify reviews into **Positive, Negative, and Neutral** categories.

I also created a **Word Cloud** using negative reviews to identify frequently mentioned words and understand the common reasons behind customer dissatisfaction.

## 🛠️ Tools & Libraries

| Tool | Purpose |
|---|---|
| 🐍 Python | Programming and analysis |
| 🐼 Pandas | Data manipulation and filtering |
| 💬 TextBlob | Sentiment analysis |
| ☁️ WordCloud | Text visualization |
| 📊 Matplotlib | Creating visualizations |
| 📁 Excel | Exporting analysis results |

## ⚙️ Project Workflow

### 1️⃣ Data Loading
- Imported the customer review dataset using Pandas.
- Explored the available customer feedback.

### 2️⃣ Sentiment Analysis
- Created a custom `get_sentiment()` function using TextBlob.
- Calculated polarity scores for each review.
- Classified reviews into three categories:

| Sentiment | Condition |
|---|---|
| 🟢 Positive | Polarity > 0 |
| 🔴 Negative | Polarity < 0 |
| 🟡 Neutral | Polarity = 0 |

### 3️⃣ Data Export
- Added sentiment labels to the original dataset.
- Exported the classified data into an Excel workbook.

### 4️⃣ Negative Feedback Analysis
- Filtered reviews with Negative sentiment.
- Combined negative feedback to identify frequently occurring words.

### 5️⃣ Word Cloud Visualization
- Generated a Word Cloud using negative customer reviews.
-The Word Cloud below highlights the most frequently occurring words in negative customer reviews and helps identify common areas of customer dissatisfaction.

![Negative Customer Review Word Cloud](Word%20Cloud%20Visualization.png)

## 📊 Key Findings

- 🔴 Product quality and performance were common areas of concern.
- 🔴 Customer support and service issues appeared frequently.
- 🔴 Words related to frustration and purchase regret highlighted negative customer experiences.
- 💡 The Word Cloud provided a quick visual summary of recurring customer complaints.

## 📂 Project Files

| File | Description |
|---|---|
| `Sentiment_Analysis.csv` | Original customer review dataset |
| `Sentiment_Analysis_Sameer.xlsx` | Sentiment-labelled Excel dataset |
| `.ipynb` | Python analysis and visualization notebook |

## 🎯 What I Learned

- Working with text data using Pandas.
- Performing sentiment analysis using TextBlob.
- Writing and applying custom Python functions.
- Using conditional statements for classification.
- Filtering and analysing negative feedback.
- Creating Word Cloud visualizations.

## 📝 Conclusion

This project helped me gain practical experience in Python-based text analysis. It demonstrated how customer feedback can be converted into meaningful insights and presented through simple visualizations.

---

<p align="center">
  <b>💻 Python | Data Analysis | NLP | Data Visualization</b>
</p>
