## Twitter Sentiment Analysis using PySpark and Naive Bayes

### Project Overview

This project focuses on analyzing sentiments of tweets using Machine Learning techniques. The goal is to classify tweets into different sentiment categories such as Positive, Negative, or Neutral. It demonstrates the use of Natural Language Processing (NLP) and data analysis techniques on real-world Twitter data.

### Objective
To analyze public opinions expressed on Twitter
To clean and preprocess text data
To build a machine learning model for sentiment classification
To evaluate model performance on real dataset

### Dataset
Source: Twitter dataset (CSV format)
Contains tweets and their corresponding sentiment labels
Features include tweet text and sentiment category

### Technologies Used
- Python
- Apache Spark (PySpark)
- Pandas
- Matplotlib
- Machine Learning
- Natural Language Processing (NLP)

### Workflow

#### 1.Data Collection
Loaded Twitter dataset from CSV file
#### 2.Data Preprocessing
Removed null values
Cleaned text (removed hashtags, links, punctuation)
Converted text into lowercase
Removed stopwords
#### 3.Exploratory Data Analysis (EDA)
Visualized sentiment distribution
Generated word frequency analysis
#### 4.Feature Extraction
TF-IDF / Count Vectorizer used to convert text into numerical form
#### 5.Model Building
Applied Machine Learning algorithms such as:
Naive Bayes
#### 6.Model Evaluation
Accuracy Score
F1 score

#### Results

- Accuracy: 85.39%
- F1 Score: 85.33%

## Author

Aiman Sarfraz

BS Data Science
