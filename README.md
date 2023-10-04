# BINet
BINet:Bio-inspired Network for Retinal Vessel Segmentation
#
All results is evaluated on Python 3.9 with PyTorch 1.11.0+cuda113.
We only publish our test results on the DRIVE, STARE and CHASE_DB1 for now.
The implementation details of code will be updated after the paper is officially published.
# Dtasets
The DRIVE, STARE and CHASE_DB1 datasets can be downloaded with:

https://drive.grand-challenge.org/

https://cecas.clemson.edu/~ahoover/stare/probing/index.html

https://blogs.kingston.ac.uk/retinal/chasedb1/
# Results
The results.zip folder contains the experimental results of our testing on the DRIVE, STARE, and CHASE_DB1 datasets.
# Tools
All the efficiency indicators are obtained on the T4 provided by the Colab platform:

    # We will prepare a notebook for training and reasoning about BINet 
    
    # You can run on the Colab platform with one click.
    
    https://colab.research.google.com/

# Reference
When building our codeWe referenced the repositories as follow:

1.[Unet](https://github.com/WZMIAOMIAO/deep-learning-for-image-processing/tree/master/pytorch_segmentation/unet)

2.[deeplav3](https://github.com/WZMIAOMIAO/deep-learning-for-image-processing/tree/master/pytorch_segmentation/deeplab_v3)

