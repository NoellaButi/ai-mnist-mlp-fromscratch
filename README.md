# MNIST Digits Classification — NumPy MLP 🔢🧠  
Multi-Layer Perceptron (MLP) with Backpropagation from Scratch in NumPy  

![Language](https://img.shields.io/badge/language-Python-blue.svg) 
![Notebook](https://img.shields.io/badge/tool-Jupyter-orange.svg) 
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)  

---

✨ **Overview**  
This project implements a Multi-Layer Perceptron (MLP) classifier for MNIST digits entirely in **NumPy**, with manual backpropagation, SGD + momentum, learning-rate decay, and optional L2 regularization & early stopping.  

The goal is to demonstrate **end-to-end understanding of neural networks without frameworks**, plus add industry-style evaluation and artifacts.  

🛠️ **Workflow**  
- Load & normalize MNIST CSV data ([0.01, 1.0])  
- One-hot encode labels  
- Xavier initialization for weights  
- Forward pass (sigmoid, softmax)  
- Backpropagation (cross-entropy + L2)  
- Train with SGD + momentum, learning rate decay, early stopping  
- Evaluate with confusion matrix, per-class metrics  

📁 **Repository Layout**  
```bash
notebooks/   # Jupyter notebook with full step-by-step pipeline
reports/     # metrics, plots, model card
artifacts/   # saved weights/biases (.npz)
README.md    # this overview
```

🚦 **Demo**

Run the Jupyter notebook:
```bash
jupyter notebook notebooks/01_mnist_mlp.ipynb
```

🔍 **Features**
- Manual forward & backward pass in NumPy
- SGD with momentum, learning-rate decay
- Early stopping and L2 regularization
- Evaluation with precision, recall, F1, confusion matrix
- Reliability diagram + Expected Calibration Error (ECE)
- Saliency maps for explainability
- Model card in `reports/`

🚦 **Results (Latest)**
```bash
Hidden layers: 1 × 256 logistic
Test accuracy: 97.64%
Correct classifications: 9,764
Incorrect classifications: 236
```

📜 **License**

MIT (see [LICENSE](LICENSE))

---
