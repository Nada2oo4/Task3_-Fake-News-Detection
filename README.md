# Task3_-Fake-News-Detection
📌 Project Overview:

This project was developed as part of the Elevvo Pathways Internship – NLP Track.
The goal of this task is to build a Fake News Detection system that classifies news articles as real or fake.
Detecting fake news is a critical NLP application with real-world impact, helping to combat misinformation and ensure trust in online information sources.

📂 Dataset:

Source: Fake News Dataset ( from Kaggle ).
Size: Thousands of labeled news articles.
Labels:
1 → Fake news
0 → Real news

🛠️ Steps Implemented:

Data Preprocessing
Removal of punctuation, special characters, and stopwords.
Tokenization and stemming/lemmatization.
Text normalization (lowercasing).
Feature Extraction
TF-IDF Vectorization.
Model Training
Classical ML models tested, such as:
Logistic Regression
Support Vector Machine (SVM)
Evaluation
Metrics: Accuracy, Precision, Recall, and F1-score.
Confusion matrix and classification report for detailed performance analysis.


📊 Results:

The models were compared across metrics.

1-Logistic Regression:
Accuracy: 0.987305122494432

2-SVM:
Accuracy: 0.9939866369710467


🚀 Technologies Used:

Python 3
Jupyter Notebook
Libraries:
pandas
numpy
scikit-learn
nltk
matplotlib
seaborn

Bonus tasks that has been done:

1-Used a word cloud to visualize common terms in fake vs. real news
