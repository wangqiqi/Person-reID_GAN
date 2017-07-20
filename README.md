# Person-reID_GAN
This repository contains the code for our paper [Unlabeled Samples Generated by GAN Improve the Person Re-identification Baseline in vitro](https://arxiv.org/abs/1701.07717).

I am reviewing the necessary codes and updating this repos. Now this repos is incomplete.

![](https://github.com/layumi/layumi.github.io/blob/master/images/fulls/gan.jpg)

### 1.Unsupervised Learning (GAN)
The first stage is to generate fake images by DCGAN.
I used the code provided in https://github.com/carpedm20/DCGAN-tensorflow and modify some hyper-parameters.

You can find my modified training code and testing code(generating image) in './DCGAN'.

### 2.Semi-supervised Learning 
The second stage is to combine the original data and generated data to train the network.
You can find the three different losses in `` , `` and ``.
