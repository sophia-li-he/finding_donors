# Finding Donors for Charity

# Installation
The libraries/packages used are:

- numpy
- pandas
- matplotlib
- sklearn
- time

# Project Motivation
The project is the first project for the [Udacity Data Scientist Nanodegree](https://www.udacity.com/course/data-scientist-nanodegree--nd025) - Term1. 

The dataset for this project originates from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Census+Income). 

The goal of this project is to accurately predicts whether an individual makes more than $50,000 using data collected from the 1994 U.S. Census. This sort of task can arise in a non-profit setting, where organizations survive on donations.  Understanding an individual's income can help a non-profit better understand how large of a donation to request, or whether or not they should reach out to begin with.

# File Descriptions
- This notebook `finding_donors.ipynb` includes the process of choosing the best candidate algorithm from several supervised algorithms and further optimizing this algorithm to best model the data.
- The python file `visualsl.py` is a supplementary visualization code that can be imported to the jupyter notebook.
- `census.csv` is the input data set for the project.
- `finding_donors_report.html` is the html output of the `finding_donors.ipynb` juypter notebook

# Results
Among three algorithms Random Forest, SVC, and AdaBoost, the final model chosen in is AdaBoost Classifier algorithm, which is short for  Adaptive Boosting. AdaBoost combines multiple “weak classifiers” into a single “strong classifier”. 

On the testing set (the rest 20%), the model predicted the outcome (Y/N) based on the classification model we generated using the training set. It yields 0.72 F$_{0.5}$ score and 0.86 accuracy score which is the highest among the three algorithms.

# Licensing, Authors, Acknowledgements
1. The project dataset  was donated by Ron Kohavi and Barry Becker, after being published in the article _"Scaling Up the Accuracy of Naive-Bayes Classifiers: A Decision-Tree Hybrid"_. You can find the article by Ron Kohavi [online](https://www.aaai.org/Papers/KDD/1996/KDD96-033.pdf).
2. Credits to https://github.com/paawan01/Titanic_dataset_analysis for the readme template

