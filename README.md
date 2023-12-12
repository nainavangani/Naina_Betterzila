# Naina_Betterzila

Title: Report on Generative Model Choice, Training Process, and Output Quality Assessment for Celebrity Face Generation using Variational Autoencoders (VAE)

## 1. Introduction

### 1.1 Background
The task of generating realistic faces from a celebrity dataset is a challenging yet intriguing problem in the field of computer vision and generative modeling. This report discusses the choice of the generative model, the training process, and an assessment of the output quality, focusing on the application of Variational Autoencoders (VAE).

### 1.2 Objective
The primary goal is to employ VAE to generate new faces that resemble celebrities from the provided dataset. This report outlines the rationale behind choosing VAE, details the training procedure, and evaluates the quality of the generated faces.

## 2. Generative Model Choice: Variational Autoencoders (VAE)

### 2.1 Rationale
VAEs are chosen for their ability to generate diverse and realistic samples while learning a meaningful latent space representation. The probabilistic nature of VAEs allows for the exploration of the latent space, facilitating controlled generation and interpolation of faces.

### 2.2 Comparison with Other Models
The decision to use VAEs is contrasted with alternative generative models like Generative Adversarial Networks (GANs) and Autoencoders. VAEs are preferred for their probabilistic nature, which aids in handling uncertainty and generating more diverse outputs.

## 3. Training Process

### 3.1 Dataset
The celebrity dataset consists of a diverse range of faces, ensuring that the model captures the various facial features and characteristics present in the celebrity population. I have used around 20000 images as my dataset.

### 3.2 Model Architecture
Details of the VAE architecture, including the encoder and decoder networks, are provided. The latent space dimensionality and other hyperparameters are discussed, with justifications for the chosen values.

### 3.3 Training Procedure
The training process involves optimizing the VAE's parameters to maximize the likelihood of generating realistic faces while simultaneously ensuring the learned latent space has desirable properties. Specifics of the loss function, optimizer choice, and training epochs are outlined.

### 3.4 Regularization Techniques
Dropout and batch normalization are used for improving the model's generalization and robustness.

## 4. Output Quality Assessment

### 4.1 Qualitative Analysis
Visual inspection and comparison of the generated faces with the real dataset are conducted. Emphasis is placed on capturing fine details, diversity, and overall visual fidelity.


I have also worked on sentiment analysis using transformer model before and you can find it here - https://github.com/nainavangani/Transformer-SMS-Spam-Detection <br>
I have also used VAE before for generarting new moon images - https://github.com/nainavangani/PaAC
