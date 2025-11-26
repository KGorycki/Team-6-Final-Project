# Team-6-Final-Project
CAP 4630-042: Intro to Artificial Intelligence
## Team Members
- Leah Brafford
- Madison Bunsen
- Kyle Gorycki
- Elisheva El-Gad
- Yaser Qazait

## Cat vs. Dog Image Classifier
- This project implements a binary image classifier that identifies whether an external image contains a cat or a dog
- We trained a custom Convolutional Neural Network (CNN) using a large Kaggle dataset and evaluated it on the test set
- Users can run the code to upload their own images and view the model’s predictions
- For best results, run each cell of the code in Google Colab with GPU runtime unless you have an IDE with the needed packages already
- Feel free to use our model in the repo: cats_vs_dogs_classifier_v4.h5 *or* train your own version!

## Features
- Custom 4-block CNN built using TensorFlow/Keras
- Strong data augmentation for improving generalization
- Early stopping to prevent overfitting
- Evaluation using accuracy, loss, confusion matrix, classification report, and plotted curves
- Interface for uploading and classifying your own images

## Dataset
We used this Cats vs Dogs dataset from Kaggle (Note: dataset too big for repo):
https://www.kaggle.com/datasets/karakaggle/kaggle-cat-vs-dog-dataset

## Code (included in our repository and colab links for clarity):
- Team6_GP.ipynb
- https://colab.research.google.com/drive/1ydPgd1bBvmjqjxYUkBuP51BabITLtSHq?usp=sharing
- Team6_GP_demo_model
- https://colab.research.google.com/drive/1RV_RHFlG6EN3XeTtk7IPSLd2N_KHdRGV?usp=sharing
