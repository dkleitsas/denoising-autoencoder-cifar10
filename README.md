# DENOISING AUTOENCODER FOR CIFAR-10

Model reconstructions with 0.4 noise

![Screenshot](reconstructions.png)


Network Architecture:

    2 Convolutional Layers
    
    2 Transposed Convolutional Layers
    
    Batch Normalization Layers


Weight Initialization:

    Kaiming Uniform Initialization


Optimization Algorithm:

    Stochastic Gradient Descent (SGD) with lr = 0.001


Training Parameters:

    Epochs: 250
    
    Batch Size: 128
