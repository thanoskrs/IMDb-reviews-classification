# IMDb-reviews-classification

We apply a classification algorithm for IMDb reviews, which is implemented using the Logistic Regression algorithm.
Each review is a vector with a value of 0 or 1, which determines whether or not a vocabulary word is present in the review.
The vocabulary includes the m most frequent words, minus n most frequent (such as: the, a, etc.), chosen by Information Gain calculation.

The aclImdb file should be included, uncompressed, in the path: IMDB-revies-classification/ 
You can download the aclImdb file here: https://ai.stanford.edu/~amaas/data/sentiment/
