
# GAN Projects Repository

This repository contains implementations of various Generative Adversarial Networks (GANs), including a Variational Autoencoder-Generative Adversarial Network (VAE-GAN) and a Simple GAN.

## Overview
Generative Adversarial Networks are a class of neural networks used for generating synthetic data that resembles real-world data. This repository demonstrates the capabilities of GANs with two projects:
1. **VAE-GAN**: Combines Variational Autoencoders (VAEs) with GANs for high-quality data generation and structured latent spaces.
2. **Simple GAN**: Implements a basic GAN architecture to introduce fundamental concepts.

## Features
- **VAE-GAN**:
  - Variational Autoencoder for encoding data into latent space
  - GAN for generating high-fidelity samples
  - Training pipeline and evaluation metrics

- **Simple GAN**:
  - Basic Generator-Discriminator architecture
  - Training and visualization of generated data
  - Useful for understanding core GAN principles

## Project Structure
- `vaeGan.ipynb`: Jupyter notebook containing the VAE-GAN implementation and experiments.
- `simpleGan.ipynb`: Jupyter notebook with the Simple GAN implementation.
- `data/`: Placeholder for datasets used in the experiments.

## Dependencies
To replicate the results or extend the projects, install the following dependencies:
- Python 3.x
- PyTorch
- NumPy
- Matplotlib
- Scikit-learn

Install them using the command:
```
pip install -r requirements.txt
```


## Usage
- Modify dataset paths in the notebooks to point to your dataset.
- Adjust hyperparameters in the configuration sections as needed.
- Run the cells sequentially to train and evaluate the models.

## Results
Results of the experiments, including generated samples and evaluation metrics, will be saved in the `voxel_outputs/` directory (or displayed in the notebook).

## Acknowledgments
These projects are inspired by research papers and existing implementations in the field of GANs. Special acknowledgment to the original GAN paper *"Generative Adversarial Nets"* and the VAE-GAN paper *"Autoencoding beyond Pixels using a Learned Similarity Metric"*.

## License
This repository is licensed under the MIT License. See the LICENSE file for details.
