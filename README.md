# 11785-Project
 ## Satellite Image Augmentation
 
This study proposes the use of generative models (GANs) for augmenting the EuroSAT dataset for the Land cover Land use (LULC) classification task. We used
DCGAN and WGAN-GP to generate images for each class in the dataset. We then explored the effect of augmenting the original dataset by about 10% in each
case on model performance. The choice of GAN architecture seems to have no apparent effect on the model performance. However, a combination of geometric
augmentation and GAN-generated images improved baseline results. Our study shows that GANs augmentation can improve the generalizability of deep classification models on satellite images.

## Directory structure.

The baseline data contains the original dataset. The dc gans output folder contains images generated for each class by DC GAN. The WGAN-GP output folder contains images generated for each class by WGAN-GP. The experiment folder contains 8 notebooks, each for one of the 8 experiments performed. The image generation folder contains the notebooks for WGAN-GP image generation experiment adapted from (https://github.com/margaretmz). The DC-GAN image generation code is adapted from (https://github.com/spmallick/learnopencv/tree/master/Deep-Convolutional-GAN/PyTorch)

Rename file is an utility for renaming generated images to the appropraite format
