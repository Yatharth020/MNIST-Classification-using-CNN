# MNIST-Classification-using-CNN
In this mini project I tried implementing Convolutional Neural Networks in keras for multi class classification problem.3 different architectures with different droputs and BatchNormalization were used and finally I tuned the best model with different parameters.

## 3 CNN Architecture and results
![alt text](https://github.com/yatscool007/MNIST-Classification-using-CNN/blob/master/table1.PNG)


Finally I used different parameters to tune the best performing model i.e. using Dropout,batchnormalization,activation function,initializers,and RMS prop optimizer


### 1. Best Model without Dropout and BatchNormalization 
![alt text](https://github.com/yatscool007/MNIST-Classification-using-CNN/blob/master/graph1.PNG)


### 2. Best Model with tanh activation and glorot Normal initialization
![alt text](https://github.com/yatscool007/MNIST-Classification-using-CNN/blob/master/graph2.PNG)

### 3. Best Model with RMS prop optimizer
![alt text](https://github.com/yatscool007/MNIST-Classification-using-CNN/blob/master/graph3.PNG)


## Results after tuning
![alt text](https://github.com/yatscool007/MNIST-Classification-using-CNN/blob/master/table2.PNG)

## Finally 5 CNN + 6 pooling +Dropout and BatchNormalization  + 1 Dense + Adam Optimizer gives us the best accuracy on test data of 99.51%.
