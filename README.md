# Sentiment Analysis of pfizer Vaccination Tweets

## Overview

This project focuses on sentiment analysis of tweets related to pfizer vaccination. It aims to classify tweets into three sentiment categories: "Negative," "Neutral," and "Positive." The sentiment analysis is performed using a logistic regression model trained on a labeled dataset of tweets.

## Dataset

The dataset used for this project is "vaccination_tweets.csv." It contains a collection of tweets along with their corresponding sentiment labels. The dataset was collected from Twitter and preprocessed for analysis.

## Preprocessing

Before performing sentiment analysis, the dataset undergoes several preprocessing steps to clean and prepare the text data:

- Text is converted to lowercase.
- URLs and special characters are removed.
- Twitter usernames and hashtags are stripped.
- Tokenization is applied to break text into words.
- Stop words are removed.
- Words are stemmed to their root form.

## Analysis

### Sentiment Analysis

Sentiment analysis is carried out using a logistic regression model. The model is trained to predict the sentiment of tweets based on their textual content.

## Results
Model Performance Our logistic regression model achieved a test accuracy of 89%. This accuracy metric reflects the proportion of correctly classified tweets out of the total test dataset. 
Classification Report: We computed a detailed classification report that includes precision, recall, and F1-score for each sentiment category in classification report below
### Model Evaluation

After building and fine-tuning the logistic regression model, we evaluated its performance on a test dataset. Here are the results:

- **Test Accuracy:** 89.47%

The model achieved an accuracy of approximately 89.47%, indicating its effectiveness in predicting sentiment.

- **Confusion Matrix:**


|            | Negative | Neutral | Positive |
|------------|----------|---------|----------|
| **Negative** | 75       | 98      | 22       |
| **Neutral**  | 0        | 1338    | 1        |
| **Positive** | 6        | 105     | 559      |



- **Classification Report:**

| Sentiment     | Precision | Recall | F1-Score |
|---------------|-----------|--------|----------|
| Negative      | 0.93      | 0.38   | 0.54     |
| Neutral       | 0.87      | 1.00   | 0.93     |
| Positive      | 0.96      | 0.83   | 0.89     |


### Conclusion

In conclusion, the logistic regression model performed well in classifying tweets into sentiment categories. It demonstrated high accuracy and provided valuable insights into public sentiment regarding pfizer vaccination on Twitter. The detailed metrics and confusion matrix allow us to understand the strengths and weaknesses of the model's predictions.

This analysis can help in understanding public sentiment trends and can be a valuable resource for decision-makers and health organizations.
