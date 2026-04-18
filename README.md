Movie Review Sentiment Analysis & Recommendation System


**Project Objective**

The goal of this project is to perform sentiment analysis on the IMDb movie reviews dataset using Natural Language Processing (NLP) techniques. The system classifies reviews into Positive and Negative categories and provides a simple recommendation based on the sentiment.

**Dataset**

**Source**: Kaggle IMDb Dataset of 50K Movie Reviews.
**Description**: 50,000 movie reviews with text and sentiment labels.

**Workflow**
1. NLP Preprocessing
To clean the raw text, the following steps were performed:


Text Cleaning: Removed HTML tags (like <br />), punctuation, and converted text to lowercase.


Tokenization: Split sentences into individual words.


Stopword Removal: Filtered out common words (e.g., 'the', 'is') that do not add value to sentiment analysis.


Lemmatization: Converted words to their base root form (e.g., "running" to "run").


**2. Feature Engineering**
Converted the processed text into numerical format using TF-IDF (Term Frequency-Inverse Document Frequency) to weigh the importance of specific words.


**3. Machine Learning Model**

Model Used: Support Vector Machine (SVM).

Accuracy: ~88%


**4. Recommendation Logic**
The system follows this logic to recommend movies:


Positive Sentiment: Recommend movie.


Negative Sentiment: Do not recommend.


Neutral Sentiment (Optional): Maybe watch.
**Evaluation Metrics**
The model was evaluated using the following metrics:


Accuracy: Percentage of correct predictions.


Precision, Recall, and F1-score: To measure the balance between classification labels.
