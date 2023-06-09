# NLP_anime
This script utilizes quotes from Kaggle datasets and web pages scraped from Zoro.to to perform sentiment analysis by extracting key phrases related to anime titles and characters. The script includes functions to check for missing values and remove any rows that contain NaN values or duplicate quotes from the dataset.
Python libraries such as NLTK are used for text preprocessing tasks like removing stopwords, lemmatizing, and correcting spelling mistakes. TextBlob is also used to perform these tasks on the quotes in the dataset.
To build predictive models, the script splits the dataset into training and testing sets and uses scikit-learn to build several machine learning models such as logistic regression, decision tree classifier, k-nearest neighbors, and Naive Bayes. These models predict the anime title based on the quote and the character who said it. The script also evaluates the models' performance using various metrics such as accuracy, precision, recall, and F1-score.
Overall, this script is a powerful tool for performing sentiment analysis on anime quotes and predicting the corresponding anime title. By utilizing advanced text processing and machine learning techniques, it can provide valuable insights into the emotional content of popular anime shows.

# New model added after our presentation on May 3rd 2023
On May 3rd 2023, after my presentation, I include BERT Model in order to analyze if this model can give us better accuracy and prediction against our sentimental analysis.
