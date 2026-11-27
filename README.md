# Customer Review Sentiment Analysis & Word Cloud (Python)
## Project Overview
This project performs automated sentiment classification and text visualization on customer product and service reviews using Python. By evaluating sentence-level polarity scores, the workflow categorizes feedback into **Positive**, **Negative**, and **Neutral** sentiments, exports the labeled dataset for reporting, and generates a word cloud to highlight the primary drivers of customer dissatisfaction.

## Tools & Libraries Used
* **Python 3**
* **Pandas:** Data loading, manipulation, filtering, and Excel export
* **TextBlob:** Natural Language Processing (NLP) for sentiment polarity scoring
* **WordCloud & Matplotlib:** Text aggregation and visual frequency mapping

## Workflow & Methodology
1. **Data Ingestion:** Loaded the raw customer feedback dataset (`Sentiment_Analysis.csv`) into a Pandas DataFrame.
2. **Sentiment Classification:** Built a custom `get_sentiment()` function using `TextBlob` polarity thresholds (`> 0` for Positive, `< 0` for Negative, `0` for Neutral) and applied it across all customer sentences.
3. **Reporting Export:** Exported the enriched dataset with sentiment labels to an Excel workbook (`Sentiment_Analysis_Sameer.xlsx`) for downstream review.
4. **Negative Feedback Isolation:** Filtered out `Negative` sentiment records and compiled the text corpus to identify recurring pain points.
5. **Visual Text Mining:** Generated a custom word cloud highlighting the most frequent terms in negative reviews (such as *product*, *purchase*, *frustration*, *customer*, *service*, and *regret*).

## Key Takeaways
* Negative feedback overwhelmingly centers around **product performance/defects** and **customer support experiences**, frequently leading to **purchase regret**.
* Isolating negative sentiment text into a word cloud provides an immediate executive snapshot of core friction areas without manually reading every review.
