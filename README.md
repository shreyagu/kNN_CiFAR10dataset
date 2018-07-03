# **USING K-NN to CLASSIFY CiFAR-10 Dataset**

Performed k-Nearest neighbours clustering algorithm on the CiFAR-10 dataset to classify test images. Also performed k-fold cross validation to find the best value of the 'k' hyper parameter and best accuracy on the dataset.

## **Requirements**
numpy
matplotlib
Python version 3.5 or later 


## **References**

The concepts used for this were derived from: 
-[CS231n Convolutional Neural Netwroks for Visual Recognition](http://cs231n.github.io/)
-[TensorFlow tutorials](https://github.com/Hvass-Labs/TensorFlow-Tutorials/)



## **Results**
The dataset was subsampled to prevent memory issues and only 10000 training samples and 1000 testing sampleds were used; the results from k-NN classification are:
- Best k = 10 
- Accuracy = 57%