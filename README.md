# Text To Image Synthesis

The objective of this project was to develop a model to generate plausible images of flower from the detailed text descriptions using GAN as a major project(undergrad).A major objective as a undregrad student was to learn recent developments in artificial intelligence and implement published paper. 


## DCGAN - Architecture

This project is the implementation of the paper: [Generative Adversarial Text to Image Synthesis](https://arxiv.org/abs/1605.05396).
![Screenshot from 2021-11-12 09-32-53](https://user-images.githubusercontent.com/21074651/141406182-18df5ae6-9924-4ac3-8381-6408dbd3373c.png)

## Requirements
- keras
- numpy

## Dataset description

The publicly available datasets used in this project are the Oxford-102 dataset of flower images having 8,192 images of flowers from 102 different categories. The dataset has been created with flowers chosen to be commonly occurring in the United Kingdom. This dataset contains only the images, but no description. Nevertheless, we used the publicly available captions collected by [Reed et al.](https://arxiv.org/abs/1605.05396) for these datasets.  Each image has five text captions that do not describe the background, and they do not mention the species of the flower.

## Codes
- downloads.py - download dataset
- glove_loader.py - downloading and handling golve model
- image_utils.py - utility module to handle image
- img_cap_loader.py - image and text loader
- dcgan.py - model
- dcgan_generate.py - file for inference
- dcgan_train.py - to train the model

## Results

![Screenshot from 2021-11-13 10-44-16](https://user-images.githubusercontent.com/21074651/141606279-1a7a91a3-0bce-40fe-b90c-5d695416f526.png)

## References
- [Generative Adversarial Text to Image Synthesis](https://arxiv.org/abs/1605.05396)
- [Generative Adversarial Model](https://arxiv.org/abs/1406.2661)
- [DCGAN in Tensorflow](https://github.com/tensorlayer/dcgan)
