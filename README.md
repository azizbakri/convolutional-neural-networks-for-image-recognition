# Image Recognition with Convolutional Neural Network
Detect objects in images.
## Getting Started
This project contains one file where you can find the code for model and a dataset that you choose by yourself what king of things you want to detect. Here I've worked on a binary prediction for dogs or cats.

## Prerequisites
* A good GPU for running the model. Incase you're runing it on a CPU, it might be better to make some changes in parameters such as images size and removing convolutional layers and neural network layers.   

**Note:** The dataset should be put in this structure:
First repository called dataset including 2 repositories called training_set and test_set where both repositories containing two repositories for two different categories that you want to predict. Also when trying to predict a new image after the model is built, add a third repository called single_prediction and put inside it the image that you want to predict.

**Note:** Depending on the dataset that the model is trained with, it can be used for detecting anything such as a dog or cat, a healthy brain or not... The code can also be modified to generate more than two outcomes.

## Built With
Python
Anaconda Spyder
Keras
Tensorflow
