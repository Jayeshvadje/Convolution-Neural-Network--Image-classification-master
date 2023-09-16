## Convolution-Neural-Network--Image-classification
### Construction of a Convolution Neural Network (CNN) for image classification.  The network is going to classify objects from the images from 10 different classes. The dataset used is a subset of CIFAR-100.


This repository includes 2 CNNs for classifying coarse (furniture and insects) and fine classes.

- Techniques used in order to improve network's accuracy:
 	Data augmentation and preprocessing
	Adam (Adaptive moment estimation)
	Reduce learning rate on plateau
	Early stopping
	Checkpoint saving

### Two models for our problem:
- The first model constructed was 2 different CNNs, one for coarse and one for fine categories as shown below.
![](https://github.com/theoVag/Convolution-Neural-Network--Image-classification/blob/master/images/im1.png)


![](https://github.com/theoVag/Convolution-Neural-Network--Image-classification/blob/master/images/im6.png)


- The second model is a Hierarchical Deep Convolutional Neural Network (based on [1]). The image below show the architecture of the approach.
![](https://github.com/theoVag/Convolution-Neural-Network--Image-classification/blob/master/images/im2.png)

#### Layers for coarse and fine classification
![](https://github.com/theoVag/Convolution-Neural-Network--Image-classification/blob/master/images/im3.png)

#### Shared Layers
![](https://github.com/theoVag/Convolution-Neural-Network--Image-classification/blob/master/images/im4.png)

#### Classification Results
![](https://github.com/theoVag/Convolution-Neural-Network--Image-classification/blob/master/images/im5.png)

