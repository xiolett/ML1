# ML1 - Lab 3: Clustering, Association Rules, and Recommenders
Central location for storing educational team projects exploring machine learning.

## Introduction
You will be using one of three different analysis methods:
* Option A: Use transaction data for mining associations rules
* Option B: Use clustering on an unlabeled dataset to provide insight or features
* Option C: Use collaborative filtering to build a custom recommendation system
Your choice of dataset will largely determine the task that you are trying to achieve. Though the
dataset does not need to change from your previous tasks. For example, you might choose to use
clustering on your data as a preprocessing step that extracts different features. Then you can use
those features to build a classifier and analyze its performance in terms of accuracy (precision,
recall) and speed. Alternatively, you might choose a completely different dataset and perform rule
mining or build a recommendation system.

## Dataset Selection and Toolkits
As before, you need to choose a dataset that is not small. It might be massive in terms of the
number of attributes (or transactions), classes (or items, users, etc.) or whatever is appropriate for
the task you are performing. Note that scikit-learn can be used for clustering analysis, but not for
Association Rule Mining (you should use R) or collaborative filtering (you should use graphlabcreate 
from Dato). Both can be run using iPython notebooks as shown in lecture.
* One example of a recommendation dataset is the movie lens rating data: http://grouplens.org/
datasets/movielens/
* Some examples of association rule mining datasets: http://fimi.ua.ac.be/data/
Write a report covering in detail all the steps of the project. The results need to be reproducible
using only this report. Describe all assumptions you make and include all code you use in the
iPython notebook or as supplemental functions. Follow the CRISP-DM framework in your analysis
(you are performing all of the CRISP-DM outline).