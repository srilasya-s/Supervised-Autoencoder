# Supervised Autoencoder 🧠

A Jupyter Notebook implementation of a **Supervised Autoencoder** — a neural network architecture that blends reconstruction and classification objectives.

---

## 📘 Overview

This repository demonstrates how to:

- Enhance a basic autoencoder with a **supervised signal**
- Jointly train it to both **reconstruct input data** and **predict labels**
- Compare performance between unsupervised and supervised autoencoder variants

The primary artifact is the `Supervised Autoencoder.ipynb`, which includes:

1. **Data preprocessing** (load, normalize, encode labels)
2. **Autoencoder architecture** definition
3. **Dual-loss training** with reconstruction + classification objectives
4. **Visualizations** for reconstructed samples and classification performance

---

## 🛠️ Requirements

- Python 3.7+ (tested on 3.8 & 3.9)
- Jupyter Notebook

### 📦 Required packages:


pip install numpy pandas scikit-learn matplotlib tensorflow

Clone the repository:


git clone https://github.com/srilasya-s/Supervised-Autoencoder.git
cd Supervised-Autoencoder
Install dependencies (see above).

Launch the notebook:

jupyter notebook
Open Supervised Autoencoder.ipynb and run each cell.

✅ Key Steps in Notebook
Autoencoder: Learn a compressed representation of data

Supervised branch: Predict target labels from encoded features

Loss functions: Combine reconstruction loss (MSE) and classification loss (cross-entropy)

Visualization: Compare original vs. reconstructed inputs, and analyze classification results

📊 Results & Insights
Adding a supervised branch typically enhances the quality of latent representations

Helps the network to learn more discriminative and informative encodings

You can experiment with:

Different model architectures (depth, units)

Loss weightings for reconstruction vs. classification

Your own dataset (modify preprocessing steps)

🧩 Extend & Customize
Try convolutional autoencoders on image datasets

Explore semi-supervised training — use both labeled and unlabeled data

Integrate with real-world datasets like MNIST, CIFAR-10, or medical records

🖋️ Author
Sri Lasya S. — srilasya‑s



