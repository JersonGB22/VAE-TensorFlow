# <h1 align="center">**VAE**</h1>

<p align="center">
<img src="images/image_readme.png"> 
</p>

This repository implements [VAE (Variational Autoencoder)](https://arxiv.org/abs/1312.6114) models, a probabilistic version of the [Autoencoder](https://github.com/JersonGB22/GenerativeDeepLearning) that compresses high-dimensional data into a more compact representation. Unlike traditional autoencoders, which assign input to a latent vector, VAEs assign input data to the parameters of a probability distribution, such as the mean and variance of a Gaussian distribution, thus creating a structured and continuous latent space. VAEs consist of an encoder and a decoder: the encoder produces matrices of means and covariances of a multivariate normal distribution with independent dimensions, while the decoder reconstructs the original data from the latent space. This approach has significant applications in image generation, data analysis, pattern recognition, and natural language processing, among other fields.

## **Implementations in TensorFlow and PyTorch**

Implementations have been conducted in TensorFlow and PyTorch, the two most widely used deep learning frameworks, to explore the capabilities of Variational Autoencoder (VAE) models, particularly Convolutional VAE models. Each implementation provides detailed insights into the differences and similarities between these frameworks, offering practical perspectives for professionals in the field.

## **Datasets Used**

- **Anime Faces**: Dataset containing 63,565 color images of [anime faces by MckInsey666](https://github.com/bchao1/Anime-Face-Dataset).

- **MNIST**: This dataset consists of 70,000 grayscale images of handwritten digits ranging from 0 to 9.

## **Results achieved by the models**

<div style="display: flex; justify-content: center;">
    <div style="display: flex; justify-content: center; max-width: 1000px;">
        <img src="images/vae_anime_faces/anime_faces_vae.gif" style="width: 500px; margin-left: -100px;">
        <img src="images/vae_mnist/mnist_vae.gif" style="width: 500px; margin-left: -100px;">
    </div>
</div>

*You can observe how generation improves as the epochs progress. For better results, you can visit the various GAN models in my [repository](https://github.com/JersonGB22/GenerativeDeepLearning).*

## **Technological Stack**
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white&labelColor=101010)](https://docs.python.org/3/) 
[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white&labelColor=101010)](https://www.tensorflow.org/api_docs)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white&labelColor=101010)](https://pytorch.org/docs/stable/index.html)
[![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white&labelColor=101010)](https://plotly.com/)

## **Contact**
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white&labelColor=101010)](mailto:jerson.gimenesbeltran@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=101010)](https://www.linkedin.com/in/jerson-gimenes-beltran/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=101010)](https://github.com/JersonGB22/)