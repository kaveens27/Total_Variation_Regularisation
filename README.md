# Combining Total Variation and Convolutional Neural Networks for Image Denoising
This repository contains code and results for a project exploring total variation (TV) regularisation and convolutional neural networks (CNNs) for removing Gaussian noise from images. The goal is to denoise images while preserving edges and key features using https://www.kaggle.com/datasets/wildlifedatasets/seaturtleidheads dataset

## Methods
Two main approaches are implemented:

Chambolle-Pock Algorithm: An efficient numerical scheme for solving the TV regularisation problem. Finds optimal regularisation parameter alpha given the ground truth and noisy images are provided.

Combined TV-NN Unrolled Algorithm: A CNN-based model integrating TV regularisation with neural networks. Estimates alpha values for denoising unseen noisy images after training on clean-noisy pairs.
