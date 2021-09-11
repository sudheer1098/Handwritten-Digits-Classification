# Handwritten_Digits_Classification

Identifying the handwritten digits using classification algorithms and also implementing GridSearchCV for Hyper parameters tuning.

### INTRODUCTION

The dataset is of 0-9 digits converted from image to input features, every row represents a specific digit image along with labels for every row. We can view the image using Matplotlib. Every digit is represented as 28x28 pixels, giving 784 features to work with.

#### Data Set Drive Link

https://drive.google.com/drive/folders/1ibzHff2uS4hUbTHI1fxihaDscA028aWm?usp=sharing

#### AIM

To apply classification algorithms and recognise the digit using the pixel intensities of the handwritten image as features.

#### APPROACH

- Import the modules and dependencies.
- Load the dataset.
- Analyse the dataset, get shape and info and check for null values and balance of the dataset.
- Plot the images of labels.
- Slice the data into features and label.
- Split the data into training dataset and testing dataset in 3:1 ratio.
- Apply feature scaling and normalization on features of training and testing datasets.
- Apply classification algorithms.
- Tune the hyperparameters using GridSearchCV.
- Compare the scores of the models and fit the best model.

#### ACCURACY

Logistic Regression : 92.11
SVM Classifier Linear : 94.0
SVM Classifier RBF : 96.92
K Nearest Neighbors : 93.90
Decision Tree Classifier : 83.75
Random Forest Classifier : 95.21
GridSearchCV model : 97.18

#### CONCLUSION

Applied different classification algorithms along with the implementation of hyper parameters tuning using GridSearchCV to predict the digit.
GridSearchCV gave pretty high accuracy – 97.18 %

<!--  -->
