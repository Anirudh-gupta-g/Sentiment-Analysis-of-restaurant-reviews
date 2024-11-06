# Sentiment-Analysis-of-restaurant-reviews
This project aims to perform sentiment analysis on restaurant reviews to classify them as positive or negative. By leveraging Natural Language Processing (NLP) techniques and a Naive Bayes classifier, the project provides insights into customer opinions and feedback trends, which can be valuable for businesses in improving customer satisfaction and making data-driven decisions.

Dataset
The dataset consists of restaurant reviews with two columns:

Review: The text of the review provided by the customer.
Liked: A binary label indicating whether the review is positive (1) or negative (0).
Each review is labeled based on its sentiment, serving as the ground truth for supervised learning.

Approach
The project follows these key steps:

Data Preprocessing:

Text Cleaning: Remove special characters and convert text to lowercase.
Tokenization: Split the text into individual words.
Stop Word Removal: Remove common but uninformative words like "is," "the," etc.
Stemming: Reduce words to their root form for better generalization.
Corpus Creation: Generate a clean, processed list of reviews.
Feature Extraction:

Bag of Words (BoW): Vectorize the processed text using the Bag of Words model, converting each review into a fixed-length vector based on word frequencies.
Target Variable: The target variable is the binary sentiment (positive or negative) of each review.
Model Building:

Naive Bayes Classifier: Trained on the vectorized reviews to classify sentiments. This classifier is effective for text classification due to its simplicity and effectiveness on smaller datasets.
Train-Test Split: The dataset is split into training and testing sets (80%-20%) to evaluate model performance.
Evaluation:

The model is evaluated using metrics like accuracy, precision, recall, and F1-score to assess its performance in classifying sentiments.
Results
The model demonstrates effective sentiment classification of restaurant reviews, providing a baseline for more advanced models or real-time applications
