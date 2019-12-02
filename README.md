## Description of files:
1. vgg19_style.py : code for loading the network parameters, and creating the feature maps.
2. utils.py : functions for loading images and computing the gram matrix 
3. style.py : main file that sets up the model, and creates the tensorflow session
4. vgg19.npy :  weights of the pre-trained network

## Instructions for running:

To run the code for style transfer, in the style.py file, change paths to the style and content images. Then simply run the code using the command:

>>> python style.py

This will automatically load the network and perform the style transfer

There is not specific dataset for this study. Any image of you choice can be used for the content image, and any artistic image can be used for the style image