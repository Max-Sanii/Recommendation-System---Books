# Recommendation System for Books
This is my Capstone project in the Applied Artificial Intelligence Program at the University of San Diego in 2022. 

## Introduction:
Recommendation systems are very common nowadays in online shopping and entertainment websites, as they can greatly help users in identifying products of interest based on their profile or historical interaction with the system. There are many approaches in creating an effective recommender system, such as collaborative filtering, content-based filtering, metadata-based filtering, and popularity-based filtering.

## Description:
This project has been undertaken to build and investigate the two recommender systems, popularity-based and content-based, with the goal of generating good recommendations for the book dataset based on the popularity of books and the similarity of book contents. While the popularity-based system is solid, returning the most popular and trendy books to all users, most of my time was spent on the content-based system as it requires more complex computation with having unique results for each user. I have put good emphasis on the vectorization phase of the content-based system, as vectorization would directly impact the accuracy of similarities between books and consequently the performance of our recommender. I experimented with four different word embedding techniques (Count Vectorizer, TF-IDF, Doc2Vec, Bert), with two of them utilizing a machine learning approach, in which we also changed their hyperparameters for further performance improvement. The efficiency and performance of these recommenders is verified by two metrics, Precision and Mean Reciprocal Rank, which are commonly used for recommender systems.

### Methods Used
* Popularity-based Recommender
* Content-based Recommender
* NLP
* Cosine Similarity
* Word Embedding
* Count Vectorizer
* TF-IDF
* Doc2Vec
* Bert
* Machine Learning
* Inferential Statistics

### Technologies
* Python
* tensorflow
* Numpy
* Scikit-learn
* Pandas
* Matplotlib

### Instructions:
Clone or download the zip file, then, extract the zip file and open the Jupyter notebook file (.ipynb) in the same folder. Finally, open the notebook in the Jupyter of your local computer or on the cloud, and run each cell.

### Data source:
https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset?resource=download
