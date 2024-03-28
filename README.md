# insulting_comment_classification
Experimentation with multiple Classification methods to decide if a comment is insulting

## Platform
Google Collab

## Programming Language
Python

## Libraries
Sklearn, Pandas, Numpy, Nltk

## Description / Goals 
1. Implement multiple Naive Bayes Classifier (sklearn) using word counts input vectors. <br> Each Classifier is implemented with one of the following features:
   1. None optimizations
   2. Lemmatization
   3. Stopwords removal
   4. Bigrams
   5. Laplace Smoothing
  
2. Implement Support Vector Machines and Random Forests Classifiers using a compound input features vector consisting of:
    * Part of Speech (POS) tags
    * Tf-idf transformations

3. Optimize the Classification results of the previous Classifiers by creating a new Classifier (Logistic Regression) trained with:
    * Word Counts Input Vectors (Best parameters combination)
    * POS & Tf-idf Input Vectors
    
We evaluate the performance of each Classifier using the Accuracy and F1-score metrics on the test set.
    
## Tips
Add the `data` directory in your `gdrive/My Drive/Colab Notebooks/` path to execute correctly

## Author
Vassilis Panagakis
