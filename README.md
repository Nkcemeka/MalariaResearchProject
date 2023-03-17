
# Malaria Research Project
This is a research project that aims to explore the use of data augmentation techniques for malaria detection purposes.

# Authors
- Chukwuemeka Livinus Nkama
- Oluwadara Adedeji
- Eugenia Mawuenya Akpo

# File Details
- identify_mislabeled_errors.ipynb evaluates the dataset for mislabeled images
- DCGANMalariaImageAugmentation.ipynb experiments with various data augmentation techniques
- CNN_Vgg19models.ipynb develops deep learning models to classify the images


# Project Goals
1. The dataset used for this project is a popular one taken from the [official NIH website](https://ceb.nlm.nih.gov/repositories/malaria-datasets/). From research
   by other authors, some of the images appear to be mislabelled. This project attempts to identify these misclassified labels using a neural network.
2. Coming up with a large dataset in developing countries can be very cumbersome. Is there a way to solve this problem using data augmentation techiques?
   By using GANS and diffusion models, we aim to generate synthetic images and see if they can play a useful role in developing efficient and effective malaria
   detectors.
3. Although the option of sparse training images might be solved using Data Augmentation, we use two models: a CNN model created from scrach and the popular 
   pre-trained VGG19 to learn to differentiate malaria-infected images from uninfected ones.
