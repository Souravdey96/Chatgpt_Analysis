# 📌 ChatGPT User Review Sentiment Analysis

This project analyzes thousands of ChatGPT user reviews to understand what users love, what frustrates them, and how sentiment has evolved over time.
By applying NLP techniques such as TextBlob sentiment scoring, keyword extraction, and phrase analysis, the project uncovers actionable insights into real user experiences.

🔍 Project Objectives

Analyze user reviews to identify overall sentiment

Extract what users appreciate the most

Identify common pain points and user frustrations

Study how sentiment changes over time

Visualize important patterns using word clouds, trends, and frequency plots

Provide recommendations to improve the ChatGPT experience

📂 Dataset Overview

The dataset contains:

Review Text – user-written feedback

Ratings (1–5 stars)

Review Date – for trend analysis

Review ID – unique identifier

🧹 Text Preprocessing

To prepare text for analysis:

Converted text to lowercase

Removed punctuation and special characters

Removed extra spaces

(Optional) Removed stopwords

Created a clean_review column for NLP tasks

This ensured clean, consistent text for high-quality sentiment detection.

🧠 Sentiment Analysis using TextBlob

Applied TextBlob to extract:

Polarity (−1 = negative, +1 = positive)

Subjectivity (0 = factual, 1 = opinionated)

Created sentiment labels:

Positive

Neutral

Negative

This helped classify and analyze reviews effectively.

📊 Visualizations
✔ Sentiment Distribution

Bar chart showing counts of positive, neutral, and negative reviews.

✔ Sentiment Trend Over Time

Plotly interactive line chart showing how sentiment evolved monthly.

✔ WordClouds

Positive WordCloud → what users love

Negative WordCloud → what frustrates users

✔ Top Phrases

Extracted bigrams & trigrams for:

Positive reviews → praise themes

Negative reviews → complaint themes

✔ Subjectivity Histogram

Shows whether reviews are emotional or factual.

❤️ What Users Love

From positive keyword and phrase analysis:

“good app”, “very helpful”, “useful tool”

Smooth performance

Helpful answers

Easy to use

Valuable for study, work, and learning

Users appreciate ChatGPT’s helpfulness, ease of use, and accuracy.

⚠️ What Frustrates Users

Negative phrases revealed major issues:

“doesn’t work”, “can’t login”

“error occurred”, “something went wrong”

“wrong answer”, “incorrect information”

Subscription too expensive

Issues after updates

These represent the main complaints from users.

📈 Trend Analysis

Sentiment trend shows:

Overall positive sentiment over time

Dips during product updates with bugs

Peaks when major improvements were released

📝 Key Recommendations

Based on insights:

Improve login stability across devices

Reduce “something went wrong” errors

Improve accuracy for factual tasks

Strengthen multilingual response consistency

Conduct thorough testing before app updates

Provide more free-tier flexibility

These would significantly improve user satisfaction.

🧰 Technologies Used

Python

Pandas (data preprocessing)

TextBlob (sentiment analysis)

Regex (text cleaning)

Matplotlib / Seaborn / Plotly (visualizations)

WordCloud (keyword visualization)


This project demonstrates how NLP can turn raw user feedback into meaningful insights.
It quantifies sentiment, visualizes trends, and extracts themes that show:

What users value

What issues need fixing

How the product evolves over time

The analysis provides both data-driven understanding and actionable recommendations.
