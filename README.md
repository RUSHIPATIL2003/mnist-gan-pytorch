# 🧠 Generative Adversarial Networks (GANs) - MNIST (PyTorch)

---

![Python](https://img.shields.io/badge/Python-3.10-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-red)
![License](https://img.shields.io/badge/License-MIT-yellow)
![Repo Size](https://img.shields.io/github/repo-size/RUSHIPATIL2003/mnist-gan-pytorch)
![Last Commit](https://img.shields.io/github/last-commit/RUSHIPATIL2003/mnist-gan-pytorch)

---

## 📌 Overview

This project implements a **Generative Adversarial Network (GAN)** using **PyTorch** to generate realistic handwritten digits from the **MNIST dataset**.

GANs consist of two neural networks:

* **Generator** → Creates fake images
* **Discriminator** → Distinguishes real vs fake images

---

## 📄 Reference & Methodology

📘 **"Generative Adversarial Networks" — Ian J. Goodfellow et al.**
https://arxiv.org/pdf/1406.2661

---

## 🚀 Key Features

* GAN implementation using PyTorch
* Fully connected Generator & Discriminator
* Adversarial training loop
* Periodic visualization of generated images
* Reproducible results (fixed random seeds)

---

## 📊 Results

Generated samples are saved in:

```
images/sample_output/
```

---

## ⚙️ How to Run

### Clone repo

```
git clone https://github.com/RUSHIPATIL2003/mnist-gan-pytorch.git
cd mnist-gan-pytorch
```

### Install dependencies

```
pip install -r requirements.txt
```

### Run notebook

```
jupyter notebook notebooks/Generative_Adversarial_Networks_(GANs).ipynb
```

---

## 🔮 Future Improvements

* Implement DCGAN
* Train on CIFAR-10
* Add TensorBoard
* Improve training stability
* Save/load checkpoints

---

## 📁 Project Structure

```
.
├── .gitignore
├── README.md
├── requirements.txt

├── images/
│   └── sample_output/
│       ├── epoch005.png
│       ├── epoch010.png
│       └── ...

├── notebooks/
│   └── Generative_Adversarial_Networks_(GANs).ipynb
```

---

## 🙏 Acknowledgements

* Ian Goodfellow et al.
* PyTorch documentation

---

## 📜 License

MIT License
