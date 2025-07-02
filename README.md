# 🚀 EfficientNet-B0 vs. B1 Comparison on CIFAR-100

![PyTorch](https://img.shields.io/badge/Framework-PyTorch-red?logo=pytorch)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue)
![Stars](https://img.shields.io/github/stars/shivanshu2109/EfficientNet-B0-vs-B1-Comparison?style=social)

> 📊 Compare training speed, accuracy, and generalization between two EfficientNet-Lite architectures built from scratch in **PyTorch**!

---

## 🧠 Project Overview

This project implements and compares **EfficientNet-Lite B0 and a mini B1** variant on the **CIFAR-100** dataset using PyTorch.  
We build the models **from scratch** to understand performance trade-offs across:

- 🏃 Training speed  
- 🎯 Validation accuracy  
- 🔍 Generalization over 100 epochs

---

## ✨ Key Features

- 🔧 **EfficientNet-Lite Implementation** – Custom modules built using PyTorch.
- 🧱 **MBConv Blocks** – Includes depthwise/pointwise convolutions, SE blocks, and skip connections.
- 🌊 **Custom Swish Activation** – Implemented as: `x * sigmoid(x)`
- 🖼️ **CIFAR-100 Dataset** – Automatically downloaded and preprocessed.
- 📊 **Side-by-Side Comparison** – Visual & quantitative comparison between B0 and mini B1.

---

### 🔍 Model Comparison

We trained two custom EfficientNet variants:
- **B0-like Model** (Baseline)
- **Mini B1 Model** (Deeper, more complex)

| Model       | Final Val Accuracy | Best Val Accuracy | Comments |
|-------------|--------------------|-------------------|----------|
| B0-like     | 34.37%             | ✅ Best performance | Stable learning |
| Mini B1     | 24.14%             | ❌ Lower accuracy  | Early overfitting |

📌 _Conclusion:_ The B0-like model generalizes better and is preferred for deployment or further improvement.
all torch torchvision matplotlib scikit-learn seaborn numpy
