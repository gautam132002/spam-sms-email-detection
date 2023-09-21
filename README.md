# SMS Spam Classification using Logistic Regression

This repository presents an AI model that can classify SMS messages as either spam or legitimate (ham) with an impressive accuracy of 95%. We employ techniques such as TF-IDF (Term Frequency-Inverse Document Frequency) and Logistic Regression as the classifier to identify spam messages from a given dataset.

## Dataset

The dataset used for this project can be found at the following URL: [SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset).

The dataset contains two main columns:
- `v1`: Contains labels for each SMS message, indicating whether it is "ham" (legitimate) or "spam."
- `v2`: Contains the actual SMS message text.

## Colab Notebook

For a detailed implementation and analysis of the SMS spam classification model using Logistic Regression, please refer to the Colab notebook available here: [Colab Notebook](https://colab.research.google.com/drive/1QahmP4UKUvApNh8GgQ26HyxcPQkgz5lZ#scrollTo=gC2OiAqSsoR7).

## Model and Techniques

We have developed our SMS spam classification model using Logistic Regression. Logistic Regression is well-suited for binary classification tasks like spam detection, where the goal is to classify messages as either "spam" or "ham."

## How It Works

1. Data Preprocessing: We preprocess the SMS message data, including text cleaning and tokenization.

2. Feature Extraction: We use TF-IDF (Term Frequency-Inverse Document Frequency) to convert the text data into numerical features that can be used by the machine learning model.

3. Model Training: We train a Logistic Regression classifier using the preprocessed and transformed data.

4. Model Evaluation: The model achieved an impressive accuracy of 95%, making it highly reliable in classifying SMS messages correctly.

## Model Accuracy

The Logistic Regression model achieved an accuracy score of 95% on the SMS spam classification task. This high accuracy demonstrates the effectiveness of the model in identifying spam messages.
