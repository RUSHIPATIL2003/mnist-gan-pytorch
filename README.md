# Generative Adversarial Networks (GANs) Architecture
---
![Python](https://img.shields.io/badge/Python-3.10-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-red)
![License](https://img.shields.io/badge/License-MIT-yellow)
![Repo Size](https://img.shields.io/github/repo-size/RUSHIPATIL2003/mnist-gan-pytorch)
![Last Commit](https://img.shields.io/github/last-commit/RUSHIPATIL2003/mnist-gan-pytorch)

---
This project implements a Generative Adversarial Network (GAN) using PyTorch to generate realistic handwritten digits from the MNIST dataset.
---
## 📄 Reference & Methodology

This implementation is inspired by the original paper:
**"Generative Adversarial Networks" by Ian J. Goodfellow et al.**
https://arxiv.org/pdf/1406.2661

The model architecture (Generator and Discriminator design) and key hyperparameters have been derived from the methodology described in the paper. The project follows the foundational GAN training procedure, where a generator learns to produce realistic samples while a discriminator learns to distinguish between real and generated data.

---
## Key Features

* Implementation of GAN using PyTorch
* Fully connected Generator and Discriminator networks
* Adversarial training framework
* Periodic visualization of generated samples
* Reproducible setup with fixed random seeds

---
## 📊 Results

The model progressively learns to generate realistic handwritten digits over training epochs.

Example generated outputs:




   Note: Generated images are saved during training in the images/gans/ directory.

---

## How to Run

1. Install dependencies:
   pip install -r requirements.txt

2. Run the notebook:
   jupyter notebook gan_mnist.ipynb

---
## Future Improvements
* Implement Deep Convolutional GAN (DCGAN) for better image quality
* Train on more complex datasets (e.g., CIFAR-10)
* Add TensorBoard for training visualization
* Improve training stability (label smoothing, batch normalization, etc.)
* Save and load trained model checkpoints


## 📁 Project Structure
.
│   .gitignore
│   README.md
│   requirements.txt
│
├── images/
│   └── sample_output/
│       ├── epoch005.png
│       └──...
│        
│
└── notebooks/
    └── Generative_Adversarial_Networks_(GAN's).ipynb


## Acknowledgements
* Original GAN paper by Ian Goodfellow et al.
* PyTorch documentation and tutorials
