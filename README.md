# MNIST

MNIST stands for "Modified National Institute of Standards and Technology"
It consists of a collection of handwritten digits that have been normalized and centered. The dataset includes 60,000 training images and 10,000 testing images, with each image being a grayscale 28x28 pixel image. The goal of using this dataset is to train a model to correctly classify the handwritten digits from 0 to 9.

![Screenshot 2023-03-09 225922](https://user-images.githubusercontent.com/80905783/224107966-38e8fb38-df45-457d-84bd-786fc823af63.png)

## Steps involved in handwriting recognition
- prerequisites 
- pre-processing image data 
- normalising & preparing the data for CNN
- implementing Convolution Neural Network using Keras API **details of individual layer in notebook**
- we will compile the model which configures the model for training, including the optimizer to be used during training, the loss function to be optimized
- using adam optimizer is used, along with the sparse_categorical_crossentropy loss function, which is appropriate for multi-class classification problems
- the model is trained for 10 epochs this means it will go through the entire training data 10 times
- evaluation and testing of data
