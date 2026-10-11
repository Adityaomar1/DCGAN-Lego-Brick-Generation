A Deep Convolutional Generative Adversarial Network (DCGAN) built using TensorFlow and Keras to generate synthetic LEGO brick images from random noise. The project uses a Generator and a Discriminator trained together through adversarial learning.

🚀 Project Overview

The goal of this project is to explore deep learning-based image generation using GANs. The Generator creates new LEGO brick images, while the Discriminator learns to distinguish real images from generated ones.

🧠 Model Architecture

1. Generator

Takes random noise as input.

Uses neural network layers to generate synthetic images.

Learns to produce realistic LEGO brick images.

2. Discriminator

Takes real and generated images as input.

Classifies images as real or fake.

Helps improve the Generator through adversarial training.

3. Training

Trains the Generator and Discriminator alternately.

Uses Binary Cross-Entropy loss.

Uses Adam optimizers to update model parameters.
