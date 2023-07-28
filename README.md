# Restaurant Reviews Analysis using NLP

## Overview

This project performs sentiment analysis on restaurant reviews using Natural Language Processing (NLP) techniques. The goal is to gain insights into customer sentiments and sentiments towards different restaurants. The analysis can help restaurant owners and managers make data-driven decisions to improve customer satisfaction and overall dining experiences.

## Technologies Used

- Python
- Pandas
- NumPy
- NLTK (Natural Language Toolkit)
- scikit-learn


## Getting Started

To run this analysis on your local machine, follow these steps:
1. Download the dataset 'Restaurant_reviewa.tsv'
2. Run the Jupyter Notebook  to perform the analysis step by step.

## Data Collection

The dataset for this analysis is loaded from a TSV (Tab-Separated Values) file named `Restaurant_Reviews.tsv`. The file contains customer reviews and corresponding sentiments (1 for positive, 0 for negative).

## Data Preprocessing

The raw text data is preprocessed to prepare it for analysis:

- Lowercasing: Convert all text to lowercase to ensure consistency.
- Tokenization: Split the text into individual words (tokens).
- Removing Special Characters: Remove any special characters, symbols, and digits from the text.
- Stopword Removal: Eliminate common words that do not contribute much to the overall meaning.
- Lemmatization/Stemming: Reduce words to their base or root form for standardization.

## Sentiment Analysis

The sentiment analysis is performed using the Naive Bayes algorithm from scikit-learn. The model is trained on the preprocessed text data to predict the sentiment (positive/negative) of each review.

## Evaluation

The model's performance is evaluated using a confusion matrix and the accuracy score. The confusion matrix shows the true positive, true negative, false positive, and false negative values, while the accuracy score indicates how well the model predicts the sentiment of the reviews.


## Conclusion

The restaurant reviews analysis using NLP provides valuable insights into customer sentiments and preferences. By understanding customer feedback, restaurant owners can identify areas for improvement, enhance their services, and ultimately increase customer satisfaction.


## License

This project is licensed under the [MIT License](LICENSE). Feel free to use and modify the code as per your requirements.

Happy analyzing! 🍔🍕🍣
