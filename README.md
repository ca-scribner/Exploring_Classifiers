This is the code developed to complete Georgia Tech CS 7641 (Machine Learning) assignment 1 (Supervised Learning).  

The objective was to fit two datasets:

* A subset of Google's Quick, Draw! dataset [here](https://console.cloud.google.com/storage/browser/quickdraw_dataset/full/numpy_bitmap/?pli=1)
* Credit card fraud detection using a dataset from Kaggle [here](https://www.kaggle.com/mlg-ulb/creditcardfraud/home)

Using five classification algorithms:

* Decision Trees
* Support Vector Machines
* Artificial Neural Networks
* Boosting (using AdaBoost)
* K-Nearest Neighbors

The code is broken up into a Jupyter Notebook for each data-algorithm combination, each of which contains a few notes describing results.  Supporting helper functions are contained in utilities.py, and data in the data folder.