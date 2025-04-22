This project aims to build a machine learning model that can accurately classify news articles as either real or fake, helping to combat misinformation. The dataset used for this project is publicly available on Kaggle: https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset

To process and understand the text data, I used Natural Language Processing (NLP) techniques including text cleaning, stopword removal, and lemmatization with the help of NLTK and spaCy. For feature extraction, I implemented the TF-IDF (Term Frequency-Inverse Document Frequency) algorithm, which helps highlight the most relevant words in a document relative to the entire dataset.

For classification, I selected the Linear Support Vector Classifier (Linear SVC) model due to its effectiveness in high-dimensional spaces like text classification. The model was trained on the cleaned and vectorized data and achieved an impressive accuracy of 99.358%.
