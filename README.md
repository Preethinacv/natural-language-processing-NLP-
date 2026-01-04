# Kindle Review Sentiment Analysis
## Description
This project analyzes Amazon Kindle reviews and predicts the sentiment (positive or negative) based on the review text and rating. 
It demonstrates classical NLP techniques such as Bag-of-Words (BOW), TF-IDF, and Word2Vec embeddings combined with machine learning models like Naive Bayes and Logistic Regression.


Understanding customer sentiment from reviews helps businesses improve products and services. 
This project also serves as an NLP and text classification learning exercise for practical applications.
## Methodology
1. **Data Preprocessing**
   - Remove neutral reviews
   - Clean text (lowercase, remove punctuation)
   - Tokenize text into words

2. **Feature Extraction**
   - Bag-of-Words (BOW)
   - TF-IDF vectorization
   - Word2Vec embeddings (optional)

3. **Model Training**
   - Multinomial Naive Bayes (for BOW / TF-IDF)
   - Logistic Regression (for TF-IDF / Word2Vec)
   - Train-test split (80:20)

4. **Evaluation**
   - Accuracy
   - Confusion matrix
   - Comparison of methods (BOW vs TF-IDF vs Word2Vec)

## Installation

Clone the repository and install the required Python packages:

```bash
git clone <your-repo-url>
cd kindle-sentiment-analysis
pip install -r requirements.txt
