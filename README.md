# TensorFlow-Creative-Applications

I am walking through my TensorFlow learning from multiple websites, but predominantly from Kadenze. These notebooks will serve as a quick intro to TensorFlow to those who are comfortable with Python in general. 

### Prerequisites
1) Python  
2) Numpy  
3) Scikit-lean  
4) TensorFlow  
5) Patience  

There are 5 modules, 
### Introduction
In the intro iPython notebook you'll find a walkthough of loading images, reshaping them, tensorflow basics like session, plotting a gaussian curve, convolution with a gaussian kernel, construction of a gabor filter and convolution with it. I also wrote code that shows how to use placeholders to do all of the above task. The image gabor filter output was produced by a convolution of skimage.data.camera with the said gabor kernel.

![Alt text](/Introduction/Gabor\ filter\ output.png?raw=true "Optional Title")

In the homework part, we collect 100 images, reshape them to the same size, find their mean and produce more convolutions.

### Training a network with TensorFlow
In this folder, we have two iPython notebooks. In [Sine wave predictor.ipynb] I implement a simple perceptron to approximate a noisy sine
function. You can see how to generaly a simple noisy sine wave, use placeholder, to use obtain training parameters like weights and biases.
The network learns in its capacity (linear model) the sine wave and obtains an MAE of ~0.42.

#### To be continued ..


