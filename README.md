# project3_G6_NLP
1:Introduction:

The main goal of the project was to build a classifier that can distinguish between fake and real news based on the article's title and content. To do that, I had to first clean and preprocess the data before feeding it into different machine learning models.
________________________________________________________________________
2:Dataset Overview

Dataset features: title, text, subject, date, label
Size and structure of the dataset

The dataset I used contains news articles with attributes like the title, full text, subject, date, and a label indicating whether the news is real or fake. The labels were binary—1 for real and 0 for fake.
_______________________________________________________________________
 3: Data Cleaning & Preprocessing

Removed missing values
Lowercased text
Removed punctuation, stopwords, and special characters
Tokenization and Lemmatization
Script:

started by cleaning the data—removing missing values, converting everything to lowercase, and stripping punctuation and special characters. I also removed common stopwords and applied tokenization and lemmatization to standardize the words.
_______________________________________________________________________
4: Feature Extraction

Used TF-IDF Vectorization
Considered unigrams and bigrams

For feature extraction, used the TF-IDF vectorizer, which gives us a sense of how important a word is to a document relative to the corpus. experimented with unigrams and bigrams to capture more context from the text.
_______________________________________________________________________
5: Models Used

-Logistic Regression

 -SVM
 
 -XGBoost
 
 -Random Forest

we trained several models to compare performance. 
_______________________________________________________________________
6: Model Comparison

Accuracy, Precision, Recall, F1-Score

After training the models,we compared their performance using metrics like accuracy, precision, recall, and F1-score. Logistic Regression performed the best overall.
_______________________________________________________________________
 7: Challenges & Learnings

Choosing the right preprocessing steps

Comparing model performance

