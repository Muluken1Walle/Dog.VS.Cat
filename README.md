                                                      Project Title: Cat vs Dog Image Classifier 
       
                                                               Introduction: 

This project aims to classify the input image as either a dog or a cat image. The image input which you give to the system will be analyzed and the predicted result will be given as output. Machine learning algorithm [Convolutional Neural Networks] is used to classify the image. 
The model thus implemented can be extended to a mobile device or any website as per the developer’s need.
             Section I :Importing the libraries
import tensorflow as tf
import os
from keras.preprocessing.image import ImageDataGenerator
KNN-NB-Projects
                                Section II : Accessing the Data
      Accessing the datset  from my Google derive as  CSV file.
How many variables does the dataset contain?
What is the data about?
What are we trying to predict here?
                                Section III : Exploratory Data Analysis
Perform some descriptive statistics and make a note of I findings
Plot appropriate graphs to understand the relation between the variables.
Point out any observations and comment on the strength of the relationships if any.
                               Section IV : Prepare data for Training!
Make a new column symptom_class with the abnormal rows as 1 and the normal rows as 0, drop the class column
Split the entire dataset into independent features and symptoms as the response variable
Normalize the variables.
                               Section IV : Training with KNN
Use train_test_split from sklearn and split the parameters and classes into train and test sets
Starting with three nearest neighbours , train your KNN model and make a note of accuracy and other diagnostics for both training and test sets.
Try with increasing the k value and check if there is any improvement in model performance. Use different value to arrive at the optimal value of k.
Evaluate your final model using appropriate metrics for classification and comment on them.
Section V : Training with Naive Bayes
Now , fit a Naive Bayes Classifier to the same data.
Train a NB model with default arguments and make a note of training and test metrics
What are your inferences on the relative performance between the KNN and NB based models?
Which of these models would you recommend and with what reasons ?
Section VI : Wraping it up ! (This is optional but good for... like spinach...)
Which of these models performed better ?
Test these two models on other datasets as well !
To get started you could try these on
