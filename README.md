# 🚀 TrendPulse — Real-Time Hacker News Trend Analyzer

## 📌 Overview

TrendPulse is an end-to-end data pipeline and machine learning project that collects, processes, analyzes, and classifies trending stories from Hacker News.
The project extracts real-time data, performs feature engineering, and applies machine learning to predict content categories and identify trending posts.

---

## ⚙️ Project Pipeline

1. **Data Collection**

   * Fetched real-time Hacker News data using REST API
   * Stored raw data in JSON format
   * Example: 

2. **Data Cleaning**

   * Removed null and duplicate records
   * Standardized columns and formats
   * Converted raw JSON into structured dataset

3. **Feature Engineering**

   * Created new features:

     * `title_length`
     * `engagement (score + comments)`
     * `comments_to_score_ratio`

4. **Exploratory Data Analysis (EDA)**

   * Analyzed category distribution
   * Identified top trending posts
   * Visualized insights using Matplotlib

5. **Machine Learning Model**

   * Converted text data using TF-IDF vectorization
   * Trained classification models:

     * Logistic Regression
     * Naive Bayes
   * Predicted categories for news titles

6. **Model Evaluation**

   * Accuracy score
   * Classification report
   * Confusion matrix

7. **Final Output**

   * Generated dataset with predictions and features
   * Stored in `trendpulse_ml_features.csv`

---

## 📂 Project Structure

```
trendpulse_task1_data_collection.ipynb
trends.json
trendpulse_task2_data_cleaning.ipynb
cleaned_trends.csv
trendpulse_task3_analysis_ml.ipynb
trendpulse_ml_features.csv
README.md
```

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* REST APIs

---

## 📊 Key Features

* Real-time data pipeline
* Feature engineering for trend detection
* Text classification using ML
* Trend ranking based on engagement
* Model evaluation and prediction analysis

---

## 🎯 Results

* Successfully classified news into categories using ML
* Identified top trending posts based on engagement
* Built a complete end-to-end ML workflow

---

## 🚀 Future Improvements

* Improve model accuracy using advanced NLP (BERT, LSTM)
* Combine text + numerical features
* Build a dashboard (Streamlit / Flask)
* Deploy as a real-time web application

