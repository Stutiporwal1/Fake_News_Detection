**Fake News Detection using Natural Language Processing**

Project Overview - This project presents a NLP pipeline to classify news articles as real or fake, using Natural Language Processing (NLP) techniques. The goal is to combat misinformation and improve media literacy.

Dataset -

Source - Fake and Real News Dataset - Kaggle (https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)
The dataset contains two classes:
  - Real news articles from verified sources
  - Fake news articles collected from suspicious or unreliable websites

 Technologies Used -

Languages : Python (Run on Google Colab)
Libraries : pandas, numpy, nltk, spaCy, matplotlib, seaborn
Model Evaluation : Accuracy, Confusion Matrix, Precision, Recall

Text Preprocessing and Feature Engineering -

Text Cleaning  
Stopword Removal  
Lemmatization (using spaCy)  
Vectorization with TF-IDF (Term Frequency-Inverse Document Frequency)

File Structure -
Fake_News_Detection
fake-news-with-tf-idf-0-99385.ipynb           # Main notebook with preprocessing and model
Comparative_Analysis(Model_Accuracy).ipynb    # Comparison of TF-IDF + Linear SVC with machine learning models (Logistic Regression, KNN, Random Forest) 
README.md                                     # Project documentation
LICENSE                                       # MIT License


**Linear SVC with TF-IDF 99.35% performed the best due to its capability in handling high-dimensional sparse data efficiently.**
