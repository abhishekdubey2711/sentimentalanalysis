# Sentiment Analysis and Visualization on IMDB Movie Reviews

### This repository contains code for sentiment analysis and visualization of the IMDB Movie Review dataset, which consists of 50,000 movie reviews. The code utilizes natural language processing (NLP) techniques and machine learning models to analyze and classify the sentiment of the reviews.

## Dataset

### The IMDB Movie Review dataset is a collection of 50,000 movie reviews labeled as either positive or negative. The dataset is available for download from kaggle , the link to the dataset is as follows 
-- https://drive.google.com/file/d/1c5upa8XNOP1scN1YZFnHHuM5oiV38QWT/view?usp=sharing

## Usage

#### 1. Clone the repository or download the code files.
#### 2. Place the IMDB Movie Review dataset file (`your_dataset.csv`) in the same directory as the code.
#### 3. Run the `sentiment_analysis.py` script.

#### The code will perform the following steps:

#### 1. Load the dataset
#### 2. Clean the data by removing punctuation, converting to lowercase, and removing stopwords
#### 3. Perform sentiment analysis using NLTK's SentimentIntensityAnalyzer
#### 4. Create word clouds for positive and negative sentiments
#### 5. Analyze the sentiment distribution
#### 6. Visualize the sentiment distribution using a pie chart
#### 7. Train a logistic regression model on the preprocessed data
#### 8. Evaluate the performance of the trained model using accuracy score, classification report, and confusion matrix

