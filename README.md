# Variational Autoencoders (VAE) and Image Reconstruction

## Important Links
1. [Streamlit Application](https://visual-search-variational-auto-encoder.streamlit.app/)
2. [Codelabs Document](https://codelabs-preview.appspot.com/?file_id=11wvYnPBgPRSQ2Vl6WJofNutzmoaWP9N-PE-SW4ksNMQ#0)

## Introduction to Variational Autoencoders (VAE)

Variational Autoencoders (VAE) are a type of generative model used in machine learning and deep learning. They belong to the family of autoencoders, which are neural network architectures designed for unsupervised learning. VAEs specifically focus on learning a probabilistic mapping between input data and a latent space, allowing for the generation of new data points.

## Streamlit Application for Image Reconstruction with VAE

This repository includes a Streamlit application that enables users to upload an image and reconstruct it using a pre-trained VAE model. The VAE model has been trained to encode and decode images, providing a unique representation of the input images in a latent space.

### Instructions

1. Clone the repository
2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
3. Run Streamlit app:

    ```bash
    streamlit run Home.py