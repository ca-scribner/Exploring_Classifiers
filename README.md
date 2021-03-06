This is the code developed to explore and compare several classification algorithms.  This was the basis for a more detailed written report.  Report available privately on request. 

The objective was to fit two datasets:

* A subset of Google's Quick, Draw! dataset [here](https://console.cloud.google.com/storage/browser/quickdraw_dataset/full/numpy_bitmap/?pli=1)
* Credit card fraud detection using a dataset from Kaggle [here](https://www.kaggle.com/mlg-ulb/creditcardfraud/home)

Using five classification algorithms:

* Decision Trees
* Support Vector Machines
* Artificial Neural Networks
* Boosting (using AdaBoost)
* K-Nearest Neighbors

For Quick, Draw! data, we try to classify baseballs vs basketballs:
![Sample Quick, Draw! Images](examples.png)

The code is broken up into a Jupyter Notebook for each data-algorithm combination, each of which contains a few notes describing results.  Supporting helper functions are contained in utilities.py, and data in the data folder (note that the data is compressed and must be uncompressed to run code).