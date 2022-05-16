                                                      Project Title: Cat vs Dog Image Classifier 
       
                                                               Introduction: 

This project aims to classify the input image as either a dog or a cat image. The image input which you give to the system will be analyzed and the predicted result will be given as output. Machine learning algorithm [Convolutional Neural Networks] is used to classify the image. 
             Section I :Importing the libraries
import tensorflow as tf
import os
from keras.preprocessing.image import ImageDataGenerator

                                Section II : Accessing the Data
      Accessing the datset  from my Google derive as  CSV file.
How many variables does the dataset contain?
What is the data about?
What are we trying to predict here?
                                Section III : Exploratory Data Analysis
Perform some Clasfication Images and make a note of I findings

                               Section IV : Prepare data for Training!
Make a new column New columns according to the Images Dog & Cats.
Split the entire dataset into independent features and symptoms as the response variable
Normalize the variables.
                            Section V:- Predict the result
      The sytem predict the image either Dog or Cat.
