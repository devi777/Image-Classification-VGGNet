## Cifar Image Classification

Courtesy: https://www.cs.toronto.edu/~kriz/cifar.html

# Introduction

This notebook is going to show how to apply VGG16 CNN Architecture on Cifar 10 using Tensorflow and Keras.
The classes of this dataset are:

**Classes** 
- 0: airplane,
- 1: automobile,
- 2: bird,
- 3: cat,
- 4: deer,
- 5: dog,
- 6: frog,
- 7: horse,
- 8: ship,
- 9: truck 

### **Train Acc.: 98.25%**

### **Test Acc.: 70.77%**

# VGG-16

VGG16 is a convolutional neural network model proposed by K. Simonyan and A. Zisserman from the University of Oxford in the paper “Very Deep Convolutional Networks for Large-Scale Image Recognition”. The model achieves 92.7% top-5 test accuracy in ImageNet, which is a dataset of over 14 million images belonging to 1000 classes. It was one of the famous model submitted to ILSVRC-2014. 

It makes the improvement over AlexNet by replacing large kernel-sized filters (11 and 5 in the first and second convolutional layer, respectively) with multiple 3×3 kernel-sized filters one after another. VGG16 was trained for weeks and was using **NVIDIA Titan Black GPU’s.**
