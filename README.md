# Fake_news_detection
This repository contains a supervised machine learning pipeline designed to identify misinformation in news articles. The project implements and compares two robust classification algorithms—Support Vector Machine (SVM) and Logistic Regression—to achieve reliable detection in real-time.
# Key Achievements
- Scalable Pipeline: Established a complete Python-based ML pipeline from raw data to model evaluation.
- High Accuracy: Optimized models to reach 80% accuracy on a 12,000+ article dataset.
- Feature Engineering: Implemented advanced NLP techniques using NLTK and Vectorization (CountVectorizer/TF-IDF) to convert text into meaningful numerical features.
# Technical Stack
- Language: Python
- Libraries: Scikit-learn (SVM, Logistic Regression), NLTK, Pandas, NumPy.
- NLP Techniques: Tokenization, Stopword Removal, Stemming/Lemmatization, and TF-IDF Vectorization.
# Pipeline Architecture
- Data Preprocessing: Cleaning text by removing punctuation, special characters, and common stopwords.
- Feature Extraction: Converting cleaned text into numerical vectors using TF-IDF or Count Vectorization.
- Model Training: Training SVM and Logistic Regression models on the 12K+ article corpus.
# Results
The optimized Logistic Regression and SVM models provided a strong baseline for identifying misinformation, demonstrating the effectiveness of word frequency and term importance (TF-IDF) in detecting language patterns characteristic of fake news.

