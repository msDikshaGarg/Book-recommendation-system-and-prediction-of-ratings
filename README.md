# Book-recommendation-system-and-prediction-of-ratings
A recommendation system that works on cosine similarity and a prediction system to predict the rating of books.

Despite having a very big following books rarely have a prediction or rating prediction system. This was
the main motivation behind this project. The purpose of the project is to analyze and compare the
performance of neural network models in predicting the rating of a book based on title using transfer
learning. The project also includes a recommendation model that uses the concept of cosine similarity.
The performance is evaluated using the accuracy of the models to predict data from the validation
samples from the dataset and the analysis of the loss function. Dataset used for this project is
Goodreads’ Best Books Ever dataset scraped from Goodreads. This dataset contains 48483 unique book
title values.
<br>

###Data: 

The [dataset](https://www.kaggle.com/meetnaren/goodreads-best-books?select=book_data.csv) used for this project is Goodreads’ Best Books Ever dataset scraped from Goodreads,
available for use on Kaggle. The dataset consists of 48483 unique book title values which have been
extensively used in the purpose of this project. The dataset also contains book ratings that have been
used as the target label in prediction. For transfer learning, Glove 6B 100d data was used contained 100
dimensional vectors of pre trained weights for each word. The text file contains 6B tokens for 400k
vocabulary words.

