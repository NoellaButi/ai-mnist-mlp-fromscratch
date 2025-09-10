# MNIST Digits Classification — NumPy MLP 🔢🧠

<p align="left">
  <img alt="MLP" src="https://img.shields.io/badge/MLP-Neural%20Network-ff69b4">
  <img alt="Backprop" src="https://img.shields.io/badge/FromScratch-Backprop-orange">
  <img alt="Status" src="https://img.shields.io/badge/Repo-Portfolio-blue">
</p>

**Author**: [Noëlla Buti](https://github.com/NoellaButi)

---

## ✨ Overview
This project implements a **Multi-Layer Perceptron (MLP)** classifier for **MNIST digits** entirely in **NumPy**, with manual backpropagation, SGD + momentum, learning-rate decay, and optional L2 regularization & early stopping.

The goal: show **end-to-end understanding** of neural networks **without frameworks**, plus add **industry-style evaluation and artifacts**.

---

## 🛠️ Workflow
1. 📥 Load & normalize MNIST CSV data ([0.01, 1.0])  
2. 🔢 One-hot encode labels  
3. ⚙️ Xavier initialization  
4. ➡️ Forward pass (sigmoid, softmax)  
5. 🔄 Backpropagation (cross-entropy + L2)  
6. 📈 Train (SGD + momentum, LR decay, optional early stopping)  
7. ✅ Evaluate with confusion matrix, per-class metrics  
8. 🔍 Industry pack: calibration (ECE), saliency maps, model card

---

## 🚦 Results (Latest)
- **Hidden layer(s):** 1 × 256 logistic  
- **Test accuracy:** **97.64%**  
- **Correct classifications:** 9,764  
- **Incorrect classifications:** 236  

📊 Confusion matrix available in [`reports/confusion_matrix.png`](reports/confusion_matrix.png).

---

## 📁 Repository Layout
- `notebooks/` → Jupyter notebook with full step-by-step pipeline  
- `reports/` → Metrics, plots, model card, run config  
- `artifacts/` → Saved weights/biases (`.npz`)  
- `README.md` → This overview

---

## 🔍 Explainability
- **Classification report** (per-class precision/recall/F1)  
- **Most-confident mistakes** visualization  
- **Reliability diagram** + **ECE**  
- **Saliency maps**  

---

## 📜 License
MIT (see [LICENSE](LICENSE))

---
