# Sentiment-Analysis-for-Social-Media-Presence

Tech Stack
1. Python
2. Pandas
3. Numpy
4. NLTK
5. Scikit-Learn
6. Google Colab
7. Kaggle API

How It Works
1. Downloads the dataset using the Kaggle API
2. Cleans tweets: removes non-letters, lowercases, removes stopwords and applies Porter stemming
3. Converts text to numbers with TF-IDF
4. Trains a Logistic Regression model on an 80/20 stratified split
5. Saves the trained model with Pickle
