# E-Commerce-Analytics-ML:
Dataset is from downloaded from Analytics Vidya ML Hackathon and consist of two file one is train and other is test and consists of five columns 'Session id', 'start time', 'end time', 'product list' and 'gender'. Product list consists of product information with category/sub_category/sub_sub_category/product. Multiple product are viewed by individual customer, so consecutive product are separated by semi column.

## Objective:
Predict gender in test dataset.

## Approach:
Before jumping directly to approach, we need to encode the features in product id using label encoder in sklearn and also create a total time spent by each user in viewing the product. Once raw data is converted to individual feature, then we can try various classifier or neural network to predict the gender of user.

#### Neural Network:
Here a neural network-based model is generated using keras library with different layers and activation function and then tested on test dataset. 
#### Classifier:
Various classifier like Naive-Bayes, Nearest Neighbour, AdaBoost, Decision tree and XGBoost are tried.

## Result:
Finally, neural network model was giving more accuracy than any other classifier.
