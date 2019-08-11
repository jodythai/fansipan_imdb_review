[Bag of Words Meets Bags of Popcorn](https://www.kaggle.com/c/word2vec-nlp-tutorial/data)
======

## Data Set

The labeled data set consists of 25,000 IMDB movie reviews, specially selected for sentiment analysis. The sentiment of reviews is binary, meaning the IMDB rating < 5 results in a sentiment score of 0, and rating >=7 have a sentiment score of 1. No individual movie has more than 30 reviews. The 25,000 review labeled training set does not include any of the same movies as the review test set.

## File descriptions

labeledTrainData - The labeled training set. The file is tab-delimited and has a header row followed by 25,000 rows containing an id, sentiment, and text for each review.

## Data fields

* id - Unique ID of each review
* sentiment - Sentiment of the review; 1 for positive reviews and 0 for negative reviews
* review - Text of the review

## Objective
Objective of this dataset is base on **review** we predict the **sentiment** (positive or negative).

## What we did
1. Load Dataset and perform EDA
2. Train model on Logistic Regression, Decision Tree, Random Forest, KNN and Support Vector Machine. Compare the report to select the most efficient one.
3. Tune the selected model to achieve higher accuracy.
4. Validate the model on K-Fold CV
5. Predict the Test data and save the result

## Predicted Result
[Download Here](https://drive.google.com/file/d/15IEUPcU5f0R3YjjTh9sYNwGDkG54WrUK/view?usp=sharing)
