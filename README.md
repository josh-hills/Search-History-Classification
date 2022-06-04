## Table of contents
* [Classification Based on User Search History](#classification-based-on-user-search-history)
* [Files](#files)
* [Results](#results)
* [Technologies](#technologies)
* [Setup](#setup)

## Classification Based on User Search History
* The purpose of this project is to see if it is possible to identify users based solely on their search histories.
* I collected the search data of 11 friends and family (it's important to us that their data stayed confidential, for this reason I didn't upload any of the data, just the python notebooks. Any data I used as an example in those notebooks are mine personally)
* I then processed this data into a cleaned data frame, and created a model to predict a user given a search term. 

## Files
* dataPreprocessing.ipynb - This file contains all preprocessing for users search histories, from html to cleaned data frame for each user.
* model.ipynb - This file shows the process of turing preprocessed data in to a model.

## Results
The best balanced accuracy I was able to get was ~%72 using logistic regression and bag of words classification, please see 3.3 in my report for more details.

## Technologies
* Python 3.9.9 
* Python NLTK 3
* scikit-learn 1.0.2
* Beautiful soup 4.8.1
* pandas 1.3.5
* numpy 1.21.5
* Other critical packages seen in my notebooks
