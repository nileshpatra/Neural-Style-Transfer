# Neural-Style-Transfer
- This repository is a style transfer using a vgg19 classifier which is a premade neural network in pytorch with 36 layers
- The series of layers of convolution and pooling layers are made along with drouput regularization
- using the gram loss , style of the second image is copied in due course of the epoch of neural net
- using the MSE loss function , the difference between target image and the initiaal image is calculated
- then there are weights assigned so that there is a resolution to the problem between the tradeoff for style transfer and keeping 
  the identity of the image
- reference : https://github.com/udacity/deep-learning-v2-pytorch/tree/master/style-transfer
