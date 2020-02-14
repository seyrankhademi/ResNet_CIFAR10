# ResNet_CIFAR10 with Google Colab 
----------------
This repository includes an Ipython notebook written by Seyran Khademi as an example document for the reproducibility project report in deep learning course (CS4240) at Delft University of Technology. In this notebook we briefly go over the original ResNet paper https://arxiv.org/abs/1512.03385 and explain the steps to reproduce the Table 6 in the paper.

----------------
The Pytorch implementation of the ResNet architecture used in the notebook is based on the publicly available code in 
1. https://github.com/pytorch/vision/blob/master/torchvision/models/resnet.py
2. https://github.com/akamaster/pytorch_resnet_cifar10.

We changed the code so that training and testing can be performed in Jupyter notebook via Google Colab.

----------------
The results from the original paper have been successfully reproduced with better or comparable results except for the ResNet1202 model since Google Colab does not support enough (16GB) memory usage on GPU for this experiment.
We also provided the pretrained models in this repository for evaluation purposes.
