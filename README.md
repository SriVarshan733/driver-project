# driver-project
# Driver Drowsiness Detection System

### ✅ Objective

With the use of drowsiness monitoring technology, accidents brought on by drivers who slept off while operating a vehicle can be avoided.This intermediate Python project's goal is to create a drowsiness detection system that can recognise when someone's eyes are closed for a brief period of time. When fatigue is found, this system will warn the driver.

### ✅ Project Context

The route is heavily travelled both during the day and at night. Long-distance travellers, bus and truck drivers, and taxi drivers all experience sleep deprivation. As a result, it is extremely risky to drive while tired. The majority of collisions are caused by drowsy driving. So, in order to avoid these troubles, we will develop a system using Python.

### ✅ Model Architecture

Convolutional neural networks developed using Keras were utilised to create the model that was employed (CNN). Convolutional neural networks are a specific kind of deep neural networks that excel at image classiﬁcation. The fundamental components of a CNN are an input layer, an output layer, and a hidden layer with potential for several layers. These layers are put through a convolution operation with a filter that multiplies their 2D matrices together.

The following layers contribute the architecture of the CNN model:

* Convolutional layer; 32 nodes, kernel size 3
* Convolutional layer; 32 nodes, kernel size 3
* Convolutional layer; 64 nodes, kernel size 3
* Fully connected layer; 128 nodes

### ✅ Dependencies 

* OpenCV – Face and eye detection.
* TensorFlow – Keras uses TensorFlow as backend.
* Keras – To build our classification model.
* Pygame – To play alarm sound.

### ✅ Project Outcome

I have created a sleepy driver alarm system in this Python project which you may use in a variety of ways. A CNN model was used to forecast the state after utilising OpenCV to recognise faces and eyes using a haar cascade classifier.
