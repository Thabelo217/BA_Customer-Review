✈️ Sentiment Analysis of British Airways Reviews from Skytrax
🧩 Overview

This project performs web scraping, data cleaning, and sentiment analysis on customer reviews of British Airways collected from the Skytrax (AirlineQuality.com)
 website.

By automating data collection and applying Natural Language Processing (NLP) techniques, this project aims to extract insights about customer satisfaction and service quality trends based on review text.

🎯 Objectives

Scrape customer reviews from multiple pages of the Skytrax website.

Clean and preprocess the textual data for analysis.

Perform sentiment classification (positive, neutral, negative) using both rule-based and machine learning methods.

Visualize sentiment distribution and evaluate model performance.

🧠 Problem Statement
Background

Airline passenger satisfaction directly influences brand perception and loyalty. However, customer reviews on websites like Skytrax are unstructured and difficult to analyze manually. British Airways, as one of the leading global carriers, receives thousands of reviews that can be mined for actionable insights.

Problem

There is no automated process to collect and analyze customer sentiments from Skytrax reviews for British Airways. Manual review analysis is inefficient and subjective.

Solution

Develop a Python-based NLP pipeline that:

Scrapes British Airways reviews using BeautifulSoup.

Cleans and preprocesses text data.

Analyzes sentiment using TextBlob and machine learning (Logistic Regression).

Visualizes and reports sentiment trends.

🧰 Tools & Technologies
Category	Tools
Programming	Python 3
Data Collection	BeautifulSoup, Requests
Data Handling	Pandas

🧩 Insights

The majority of reviews are positive, suggesting overall satisfaction.

Negative reviews focus primarily on service delays and flight cancellations.

The machine learning model achieved ~74% accuracy with a simple logistic regression approach.

🧑‍💻 Author

Thabelo Mudzanani

Email: thabelo217@gmail.com 
Linkedin: https://www.linkedin.com/in/thabelo-mudzanani/#:~:text=www.linkedin.com/in/thabelo%2Dmudzanani


NLP & Text Processing	NLTK, TextBlob
Machine Learning	Scikit-learn
Visualization	Seaborn, Matplotlib
