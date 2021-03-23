# Movie-Genres-Classification-from-their-Poster-Image-using-CNNs
# Classification des genres  de films à partir des affiches/images utilisant CNNs
## Introduction
### Description du problème 

Ce projet a pour objectif de parvenir à une classification des genres de films basée uniquement sur des des affiches de films.
Pour les spectateurs, les affiches de films sont très significatifs  pour avoir une idée du contenu du film et de son genre. Les humains peuvent se faire une idée en fonction de choses comme la couleur, les objets, les expressions sur les visages des acteurs, etc. pour déterminer rapidement le genre (horreur, comédie, animation, etc.).
If humans are more or less able to predict genre of a movie only giving a look at its poster, then we can assume that the poster possesses some characteristics which could be utilized in machine learning algorithms to predict its genre.

### Proposed Approach

In order to do that a Deep Neural Network (Convolutional Neural Network) is constructed to classify a given movie poster image into genres. Since a movie may belong to multiple genres, this is a multi-label image classication problem.

First of all, we use an online available IMDB dataset (source: https://www.kaggle.com/neha1703/movie-genre-from-its-poster) collected from the most famous movie website (https://www.imdb.com/).
Using the IMDB link of each movie (available in this dataset) we use a Web Scraping approach in order to retrieve its poster image from the IMDB movie page and save it locally. Once this is done, we can finally construct our Convolutional Neural Network in order to classify movie genre basing on poster characteristics.

Note: since even a human can easily make mistakes in this task, our initial goal is to recognize correctly at least half of the movies.

(sources and related links: 
https://www.depends-on-the-definition.com/classifying-genres-of-movies-by-looking-at-the-poster-a-neural-approach/
https://www.kaggle.com/neha1703/movie-genre-from-its-poster
https://towardsdatascience.com/building-a-convolutional-neural-network-cnn-in-keras-329fbbadc5f5)
