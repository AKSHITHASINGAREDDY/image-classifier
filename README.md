# image-classifier

This repository contains code and blog on how to build a image Classifier to classify three objects. They are: 
 1. airplane
 2. motorbike
 3. schooner

## Libraries
 This project is completed using python as programming language. 
 Libraries used are:
 1. TensorFlow - Deep learning module which helps in building deep learning models
 2. Matplotlib - Python module used for Visualizations
 3. NumPy - Python module used to array transformations while building models

 To accomplish this assignment, we have used convolutional neural networks, otherwise referred as CNN’s. 
CNN is a deep learning algorithm mainly used for image inputs. Convolutional layers are the primary 
building blocks of a CNN. Convolution layer typically takes an image input (a matrix ) and do convolution 
operations with the kernel and forward the output matrix to next layer. Here, kernel is the learnable 
parameters which are learned over the training time. At each epoch, as the training images are fed, based 
on the loss these kernels are learnt during back propagation. Typically, a Convolutional Neural Network has 
three different types of layers. They are:
 1. Convolutional Layer - Given an input, it performs the convolutional operations on input followed by 
activation function and passes the result as an output. Typically the activation function is RELU which 
stands for rectified linear units.
 2. Pooling layer - pooling layers are used in network to decrease the dimensionality of the feature map. 
There are different types of pooling layers. Broadly, different pooling layers are MaxPooling, 
AvergaePooling, GlobalAveragepooling
 3. Fully Connected Layer - After a series of convolution and max pooling layers, input is flattened out and 
sent to fully connected layers. In this type of layers, unlike CNN, every node is connected to every node 
in next layer.

 For building a model, we are using TensorFlow module. It is an opensource module developed by google 
which eases the process of preparing data, building model and evaluation model. Classifier was 
programmed in colab using GPU provided by colab. 
Below are the steps involved in building image classifiers:
 1. Splitting data
 2. Building data pipelines
 3. Data Visualization
 4. Create Model
 5. Train Model
 6. Evaluate Model
 7. Save Results
 

## Usage

code is in the form of jupyter notebook. You can run the notebook using the following command:

    jupyter notebook

It will open the jupyter notebook in your browser. You can run the code cells in the notebook.

## Blog

You can read the blog on this project [here](https://akshithasingareddy.wixsite.com/2022/post/image-classification).

For any queries, feel free to open an issue.
