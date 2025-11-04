Movie Review Sentiment Classifier

A Machine Learning mini project to classify IMDB movie reviews into positive or negative sentiments using Logistic Regression and Random Forest classifiers in Python.

Overview
This project builds a sentiment analysis model using two classical machine learning algorithms—Logistic Regression and Random Forest—on the popular IMDB movie review dataset. The goal is to demonstrate the end-to-end workflow: data cleaning, feature extraction, model training, and performance evaluation.

Dataset
Source: IMDB 50K Movie Reviews Dataset (Kaggle)

Format: CSV with two columns—review (text) and sentiment (positive or negative)

Workflow
Load and inspect the dataset

Preprocess text (clean HTML tags, remove non-letters, convert to lowercase)

Convert text to vectors using TF-IDF

Split data into training and testing sets

Train models: Logistic Regression & Random Forest

Evaluate and compare model performance with classification reports and accuracy

Usage
Clone this repository or download the code files.

Download the IMDB dataset from Kaggle and upload it to your working directory as IMDB Dataset.csv.

Run the Jupyter Notebook or Python script (.ipynb or .py).

All libraries used are standard (pandas, scikit-learn, etc.) and available on Google Colab or installable with pip.

Example Code Snippet
python
import pandas as pd
df = pd.read_csv('IMDB Dataset.csv')
# ...text preprocessing...
# ...TF-IDF...
# ...train/test split...
# ...logistic regression & random forest training...
# ...evaluation and classification report...
Results
Logistic Regression and Random Forest both achieve high accuracy on the full IMDB dataset.

Outputs include accuracy score and full classification report (precision, recall, f1-score).

Requirements
Python 3.x

pandas

scikit-learn

(optional) Google Colab for cloud computation

Project Structure
text
├── IMDB Dataset.csv
├── Sentiment_Classifier.ipynb
├── README.md
Credits
IMDB dataset: Kaggle

Inspired by ML/NLP best practices and open community tutorials
