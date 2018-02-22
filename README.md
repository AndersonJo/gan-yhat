# gan-yhat
GAN implementations with PyTorch

The followings are a list of GAN implemented here.

1. Vanilla GAN
    - Vanilla GAN for MNIST
    - Vanilla GAN for Fashion MNIST
2. Conditional GAN for MNIST
3. DCGAN for Fashion MNIST
4. Improved GAN
    - Feature Maching 
5. AnoGAN

## Vanilla GAN

#### MNIST 

It shows a little bit of mode collapse; a commonly encountered failure case for GANs where the generator produces samples with extremely low variety. In this case, the generator produces `1` with extremely high probability. 

![MNIST](images/vanilla_mnist.png)

## Conditional GAN

Conditional GAN reduces mode collapse issue by giving the model additional information. 

![Conditional GAN](images/conditional_gan.png)

## DCGAN

DCGAN makes use of convolutions and transposed convolutions. 

![Conditional GAN](images/dcgan.png)

![Conditional GAN](images/dcgan2.png)

![Conditional GAN](images/dcgan3.png)

## RNN GAN

#### Sin 

It uses feature mapping and LSTM.

![Sin](images/rnngan-sin.png)

## Improved GAN

#### Feature Matching

![Conditional GAN](images/feature-matching1.png)

![Conditional GAN](images/feature-matching4.png)

## AnoGAN

Anomaly Detection with GAN

#### Anomaly Detection for Normal Data

The following images are normal images. 

> It is good if red dots are less shown. 

![Normal1](images/ano_normal1.png)

![Normal1](images/ano_normal2.png)

![Normal1](images/ano_normal3.png)

![Normal1](images/ano_normal4.png)

![Normal1](images/ano_normal5.png)

