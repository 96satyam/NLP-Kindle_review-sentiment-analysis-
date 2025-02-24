# NLP-Kindle_review-sentiment-analysis-

###  Kindle Review Sentiment Analysis using Word2Vec & Random Forest
🚀 Project Overview
This project applies Natural Language Processing (NLP) and Machine Learning to analyze sentiment in Kindle book reviews. We leverage Word2Vec to generate word embeddings and train a Random Forest Classifier to predict sentiment (positive or negative).

📊 Tech Stack
Python 🐍
Pandas, NumPy for data handling
NLTK, Gensim for text preprocessing & Word2Vec
Scikit-learn for model training & evaluation
Matplotlib, Seaborn for visualization
🔎 Workflow
1️⃣ Data Preprocessing

Tokenization, stopword removal, and text cleaning
2️⃣ Train-Test Split
Split data before training Word2Vec to prevent data leakage
3️⃣ Word2Vec Embeddings
Train Word2Vec on X_train and convert text into fixed-length vectors
4️⃣ Random Forest Model
Train on sentence embeddings and predict sentiment
5️⃣ Evaluation & Visualization
Accuracy, Confusion Matrix, and Feature Importance
📈 Results & Insights
✔ High accuracy achieved using Word2Vec & Random Forest
✔ Word embeddings capture meaningful semantic relationships
✔ Feature importance analysis helps in understanding model decisions
