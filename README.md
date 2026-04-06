# 🚀 TrendPulse — Real-Time Trend Analysis & ML-Based Category Prediction

TrendPulse is an end-to-end data pipeline that collects, processes, and analyzes trending posts from Hacker News. The project applies feature engineering and machine learning to classify posts into categories and extract insights from real-time data.

---

## 📌 Project Workflow

This project follows a structured pipeline:

1. **Data Collection**

   * `trendpulse_task1_data_collection.ipynb`
   * Collects real-time trending posts using Hacker News API

2. **Raw Data Storage**

   * `trends.json`
   * Stores collected raw data

3. **Data Cleaning & Preprocessing**

   * `trendpulse_task2_data_cleaning.ipynb`
   * Cleans missing values, removes duplicates, and structures data

4. **Cleaned Dataset**

   * `cleaned_trends.csv`
   * Ready for analysis and machine learning

5. **Feature Engineering & ML**

   * `trendpulse_task3_analysis_ml.ipynb`
   * Creates features and trains ML model

6. **Final Output**

   * `trendpulse_ml_features.csv`
   * Contains engineered features + predicted categories

---

## ⚙️ Tech Stack

* Python
* Pandas
* Matplotlib
* Scikit-learn
* TF-IDF (Text Feature Extraction)
* Logistic Regression

---

## 🧠 Key Features

* Real-time data collection from Hacker News API
* Data cleaning and preprocessing pipeline
* Feature engineering:

  * Title length
  * Engagement score (score + comments)
  * Comments-to-score ratio
* Text vectorization using TF-IDF
* Category prediction using Logistic Regression
* Model evaluation using accuracy and classification report
* Prediction on new unseen titles

---

## 📂 Project Structure

TrendPulse

│
├── trendpulse_task1_data_collection.ipynb
├── trends.json│

├── trendpulse_task2_data_cleaning.ipynb
├── cleaned_trends.csv│

├── trendpulse_task3_analysis_ml.ipynb
├── trendpulse_ml_features.csv


---

## 📊 Model Details

* Input: Post titles
* Output: Category prediction
* Feature Extraction: TF-IDF
* Algorithm: Logistic Regression

---

## 📈 Results

* Built a complete end-to-end ML pipeline
* Generated predictions for all posts
* Converted raw data into structured, insight-driven output

---

## 🎯 Learning Outcomes

* Developed a full data pipeline (collection → cleaning → ML)
* Applied NLP techniques for text classification
* Performed feature engineering on real-world data
* Evaluated model performance using standard metrics

---

## 🚀 Future Improvements

* Improve accuracy using advanced ML models
* Add sentiment analysis
* Build a real-time dashboard
* Deploy as a web application

