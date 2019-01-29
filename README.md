# Project: Dog Breed Classifier
Udacity Deep Learning Nanodegree program 2019. In this project, I develop an algorithm for a dog identification application, a dog breed image classifier.

## Project Overview
In this project, I built a convolutional neural network (CNN) that can identify whether the given image is either a dog or a human or none. If a dog is detected, then the code will identify the dog breed. Otherwise, if a human is detected, the code will identify the resembling dog breed.

<img src="assets/sample_dog_output.png">

The project there is seven steps:
- _Step 1:_ Detect Humans
- _Step 2:_ Detect Dogs
- _Step 3:_ Create a CNN to Classify Dog Breeds (from Scratch)
- _Step 4:_ Use a CNN to Classify Dog Breeds (using Transfer Learning)
- _Step 5:_ Create a CNN to Classify Dog Breeds (using Transfer Learning)
- _Step 6:_ Write your Algorithm
- _Step 7:_ Test Your Algorithm

The code is written in Python 3 and [Keras](https://keras.io/) with [Tensorflow](https://www.tensorflow.org/) backend all presented in Jupyter Notebook.

### Prerequisites
Thinks you have to install or installed on your working machine:

- Python 3
- Numpy
- Glob
- OpenCV
- Tqdm
- Matplotlib
- Jupyter Notebook
- Keras

## Jupyter Notebook
- `dog_app.ipynb`

This jupyter notebook describe the whole project from udacity, from the beginning to the end.

## Download the Datasets
To train and test the model, you need to download of two datasets. Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip). Unzip the folder and place it in this project's home directory, at the location `/dog_images`. After downloading the [human dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip). Unzip the folder and place it in the home directory, at location `/lfw`.

## Running the project
The whole project is located in the file `dog_app.ipynb` and it's include the training and the prediction part.
To open the project [click here](https://github.com/buzutilucas/dog-breed-classifier/blob/master/dog_app.ipynb)
