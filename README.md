# Amazon-Kindle-Reviews-Sentiment-Analysis
Developed a sentiment analysis project using Python, NLP, and Machine Learning to classify Amazon Kindle reviews as positive or negative. Applied text preprocessing, lemmatization, Bag of Words, TF-IDF, and Naive Bayes classification to analyze customer opinions and evaluate model performance.
# Amazon Kindle Reviews Sentiment Analysis

## Project Overview
This project uses Natural Language Processing (NLP) and Machine Learning to analyze Amazon Kindle customer reviews and classify them as positive or negative.

## Objectives
- Analyze customer reviews and sentiment.
- Clean and preprocess text data.
- Convert text into numerical features.
- Train sentiment classification models.
- Evaluate model performance using accuracy and confusion matrices.

## Dataset
The dataset contains Amazon Kindle Store reviews collected between May 1996 and July 2014.

**Source:** Julian McAuley, UCSD Amazon Product Data  
http://jmcauley.ucsd.edu/data/amazon/

The project uses the `reviewText` and `rating` columns.

## Technologies Used
- Python
- Pandas
- NLTK
- Regular Expressions
- BeautifulSoup
- Scikit-learn
- NLP
- Machine Learning
- Jupyter Notebook

## Project Workflow

### 1. Data Loading and Exploration
Load the CSV dataset and examine its shape, missing values, and rating distribution.

### 2. Text Preprocessing
- Convert text to lowercase.
- Remove special characters and URLs.
- Remove English stopwords.
- Remove HTML tags.
- Remove extra spaces.
- Apply lemmatization.

### 3. Sentiment Classification
Convert ratings into binary labels:
- **Negative (0):** Rating below 3.
- **Positive (1):** Rating of 3 or above.

### 4. Train-Test Split
Split the dataset into 80% training data and 20% testing data.

### 5. Feature Extraction
- **Bag of Words (BoW):** Represents reviews using word counts.
- **TF-IDF:** Represents reviews using word importance scores.

### 6. Model Training
Train Gaussian Naive Bayes classifiers using BoW and TF-IDF features.

### 7. Model Evaluation
Evaluate the models using:
- Accuracy Score
- Confusion Matrix
- Classification Report

## Applications
- Customer feedback analysis
- Product review classification
- Customer satisfaction analysis
- E-commerce sentiment analysis

## Future Enhancements
- Compare Logistic Regression and Multinomial Naive Bayes.
- Experiment with Word2Vec embeddings.
- Improve classification performance.
- Detect suspicious reviews.
- Build a web application for sentiment prediction.

## How to Run

Install the required libraries:

```bash
pip install pandas numpy nltk beautifulsoup4 lxml scikit-learn jupyter
```

Place `all_kindle_review.csv` in the project directory and run the notebook cells sequentially.

## Author
Divya Rahane
