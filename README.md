## Intro:

This is an implementation of the style transfer algorithm (https://arxiv.org/pdf/1508.06576.pdf) in tensorflow without using Keras API's.

## Description of files:
1. vgg19_style.py : code for loading the network parameters and creating the feature maps.
2. utils.py : functions for loading images and computing the gram matrix 
3. style.py : main file that sets up the model, and creates the tensorflow session
4. vgg19.npy (to be downloaded):  weights of the pre-trained network

## Instructions for running:

Before running the code, download the pretrained vgg 19 weights from https://github.com/tensorlayer/pretrained-models/blob/master/models/vgg19.npy and place the weights file in the root directory.

To run the code for style transfer, change paths to the style and content images in style.py. Then simply run the code using the command:

> python style.py

This will automatically load the network and perform the style transfer

There is no specific dataset for this study. Any image of you choice can be used for the content image, and any artistic image can be used as the style image