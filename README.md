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

## 🆚 Models Compared

| Model                | Width Coeff | Depth Coeff | Description                          |
|---------------------|-------------|-------------|--------------------------------------|
| EfficientNet-Lite B0 | 1.0         | 1.0         | ✅ Baseline version                  |
| EfficientNet-Lite B1 (Mini) | 1.2         | 1.4         | 🚀 Slightly deeper & wider version |

---

## ⚙️ Setup and Usage

### 📦 Requirements
```bash
pip install torch torchvision matplotlib scikit-learn seaborn numpy
