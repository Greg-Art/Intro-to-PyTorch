# 🔥 PyTorch Crash Course – Aladdin Persson

Welcome to my personal implementation of the **[PyTorch Beginner Tutorial](https://www.youtube.com/watch?v=V_xro1bcAuA)** by [Daniel Bourke](https://www.youtube.com/watch?v=LyJtbe__2i0&t=386s). This project walks through core deep learning concepts using PyTorch — from tensors to training neural networks and working with custom image datasets.

---

## 📘 What I Learned

- 🧮 **Tensor Operations** – Creating, manipulating, and computing with tensors
- 🔁 **Autograd & Gradients** – Backpropagation and gradient tracking using `autograd`
- 🧠 **Model Building** – Building linear and deep neural networks using `torch.nn`
- ⚙️ **Training Workflows** – Custom training/testing loops, optimizers, and loss functions
- 🎯 **Classification** – Binary and multi-class classification with softmax & accuracy tracking
- 🖼️ **Computer Vision** – Training CNNs with TorchVision and running experiments on GPU
- 🗃️ **Custom Datasets** – Creating custom `Dataset` and `DataLoader` classes + augmentations
- 💾 **Model Saving & Evaluation** – Saving/loading models, plotting results, confusion matrix
- 🧩 **Modular Design** – Clean and scalable PyTorch project structure using reusable components

---

## 🧠 Course Modules Overview

| Module             | Topics Covered                                           |
|--------------------|-----------------------------------------------------------|
| **Fundamentals**   | Tensors, tensor ops, matrix math, device agnosticism     |
| **Workflow**       | Linear regression from scratch, training loop basics      |
| **Classification** | Binary + multiclass classification with `nn.Sequential`   |
| **Computer Vision**| Convolutional Neural Networks (CNNs), TorchVision         |
| **Custom Datasets**| Pizza/Steak/Sushi classifier with custom `Dataset` class |
| **Modularization** | Breaking into `data.py`, `model.py`, `train.py`          |

---

## 🗂️ Folder Structure

pytorch-crash-course/ │ ├── notebooks/ # Jupyter notebooks per lesson ├── datasets/ # Sample + custom datasets ├── models/ # Model definitions (CNNs, classifiers, etc.) ├── utils/ # Plotting, metrics, helper functions ├── outputs/ # Saved models, plots, predictions └── README.md # This file



---

## 🚀 Getting Started

### 📥 Clone the Repository

```bash
git clone https://github.com/yourusername/pytorch-crash-course.git
cd pytorch-crash-course


pip install torch torchvision matplotlib numpy jupyter


jupyter notebook
