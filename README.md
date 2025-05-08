
Generative Models With AE, VAE and GANs
==============================


## 📚 Overview
This lab introduces three fundamental generative models in deep learning:

### Autoencoder (AE) 

A simple autoencoder network.

![image](https://github.com/user-attachments/assets/612bce3d-6bcf-4193-be6d-7c3fed498338)

### Variational Autoencoder (VAE)

The original variational autoencoder network,  using tensorflow_probability

![image](https://github.com/user-attachments/assets/d980fb98-60a5-4666-af4b-4e5a92962d8c)


### Generative Adversarial Network (GAN) 

GANs are a form of neural network in which two sub-networks (the encoder and decoder) are trained on opposing loss functions: an encoder that is trained to produce data which is indiscernable from the true data, and a decoder that is trained to discriminate between the data and generated data.

![image](https://github.com/user-attachments/assets/9a82a40a-21db-48eb-a4d5-4679df8a862d)


All models are implemented using **Python**, **TensorFlow/Keras**, and trained on the **MNIST** dataset.

## 🧰 Development Environment

### Requirements
You can install the dependencies using `pip`:
- numpy
- matplotlib
- soundfile
- tqdm
- pandas
- tf-nightly-2.0-preview==2.0.0.dev20190513
- tfp-nightly==0.7.0.dev20190508

### Python Packages
- tensorflow >= 2.10
- numpy
- matplotlib
### Dataset
MNIST will be downloaded automatically using TensorFlow Datasets.

## 🚀 How to Run the Notebook
1. Launch the Jupyter Notebook

2. Open the notebook files in the repo: `Generative_Models_AE_VAE_GAN.ipynb`

3. Run each cell in sequence.

## 📈 Output Expectations
- AE and VAE: Visualization of reconstructed digits.
- VAE: Sampling from latent space and generated digits.
- GAN: Training progress and fake vs real image comparisons.

## ✍️ Authors
-	Noureddine MOUHSSINE
-	Abdellah SANBA

