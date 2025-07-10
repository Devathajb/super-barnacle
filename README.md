#Sentiment-Analysis-using-python
# 📦 Amazon Product Reviews Sentiment Analysis

This project uses **Natural Language Processing (NLP)** and **Machine Learning** to analyze Amazon product reviews and predict whether a review is **positive** or **negative**.

---

## 💡 Objective

To build a sentiment analysis model that can handle large datasets and automatically classify reviews as **positive** or **negative** based on the review text.

---

## 🧠 Techniques Used

- **Text Cleaning and Preprocessing**
- **TF-IDF Vectorization**
- **Machine Learning Classification Models**
- **Model Evaluation**
- **Data Visualization (WordCloud, Bar Charts)**

---

## 🗂️ Dataset

The dataset consists of Amazon product reviews. It has been preprocessed for ease of use. You can download the dataset using the provided link before running the code.

---

## 🚀 Steps to Run the Project

### 1. 📥 Import Libraries and Load Dataset

The following libraries are used:
- `pandas` – for data loading and manipulation
- `sklearn` – for ML models and TF-IDF Vectorizer
- `matplotlib` – for plotting and visualization
- `wordcloud` – for generating word clouds
- `warnings` – to suppress unnecessary warnings

### 2. 🧹 Data Preprocessing

- Cleaning the reviews
- Removing stopwords, punctuations, and applying lowercase
- Labeling sentiment as binary (positive/negative)

### 3. 📊 Data Analysis

- Word frequency analysis
- Word clouds
- Distribution of sentiments

### 4. 🔤 Text to Vector Conversion

- Using **TfidfVectorizer** to convert text into numerical format suitable for ML algorithms.

### 5. 🏋️ Model Training and Evaluation

- Splitting data into train and test sets
- Training a classification model (like Logistic Regression or Naive Bayes)
- Evaluating using accuracy, precision, recall, and F1-score

### 6. 🔍 Making Predictions

- Predicting sentiment for new/unseen reviews

---
