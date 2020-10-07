# Sentiment Analysis- Movie Reviews Classification
Classification movie reviews as positive or negative using the following two approaches and
comparing their accuracy.

Approach 1 - Word Count Vectorization
Two files are provided: reviews.txt and labels.txt. 
Each line in reviews.txt correspond to a textual review for a movie. The corresponding line in the
label files will have the label - NEGATIVE and POSITIVE, which is a binary sentiment inferred by
reading the review. The files contain reviews and labels for 25000 different movies.
Calculating a feature for each word, based on the word counts for the positive and negative reviews,
that can indicate the sentiment of the review.

Approach 2 - Neural Network Based Sentiment Classification
Creating a single hidden layer, multi-layer perceptron (MLP), that is evaluated on the test review data.
