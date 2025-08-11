## 📌 Project Overview

This project performs text mining, sentiment analysis, and association rule mining on a Turkish news dataset.
It uses Natural Language Processing (NLP) techniques to clean, tokenize, and analyze textual data, then applies statistical and visualization methods to uncover patterns, sentiment polarity, and frequent word associations.

The dataset contains Turkish news texts, and the workflow includes:
- Text preprocessing (lowercasing, punctuation and number removal, stopword removal, whitespace cleaning)
- Tokenization into words
- Word frequency analysis
- Sentiment polarity detection (positive/negative)
- Word cloud visualization
- Association rule mining using Apriori algorithm
- Visualization of rules and frequent itemsets

## 📂 Files in the Project
- haber.txt → Raw news text data.
- ref.StopWordListTR.csv and stopwords-tr.txt → Turkish stopword lists.
- TurkishSentiment-positive.txt and TurkishSentiment-negative.txt → Lists of positive and negative Turkish sentiment words.
- text_mining.Rmd → R Markdown file containing all the code, analysis, and visualizations.

## 📈 Results
The analysis of Turkish news articles revealed several key insights:
Word Frequency: The most frequently occurring words in the dataset were related to current events, politics, and economic terms, indicating the strong presence of these topics in the selected news corpus.
Sentiment Analysis: The polarity analysis showed that the overall tone of the news articles was predominantly neutral to slightly negative, with negative sentiment being driven by words associated with crises, conflicts, and economic downturns, while positive sentiment terms were mostly related to development, achievements, and cultural events.
Association Rules: Market basket analysis highlighted significant co-occurrence patterns between certain words, suggesting common narrative structures or thematic clustering in the articles.
Visualization Outcomes: Word clouds and frequency plots made it visually evident which terms dominate Turkish media discourse, while bar plots and graphs confirmed the distribution of sentiment and thematic groupings.
Overall, the results show that Turkish media content in the analyzed dataset leans toward reporting impactful and often challenging events, with sentiment patterns reflecting the socio-political climate of the time. This project demonstrates how text mining and sentiment analysis can uncover both quantitative and qualitative aspects of media coverage.

## 📬 Author
Prepared by: Melda Korkudan
Purpose: Academic research and Turkish text mining demonstration.
