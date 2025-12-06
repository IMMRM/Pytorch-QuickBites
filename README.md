# Pytorch-QuickBites

A **12-Day PyTorch Learning Roadmap** built as a sequence of hands-on Jupyter notebooks.  
Each notebook delivers a focused, digestible “quick bite” introducing a core PyTorch concept through concise explanations and runnable code.

> **Note:** The repository currently contains **Day1–Day12** notebooks. Two additional days can be added later if you intend the full 12-day roadmap.

---

## Table of Contents

- [About](#about)  
- [Goal](#goal)  
- [Daily Roadmap Overview](#daily-roadmap-overview)  
- [Requirements](#requirements)  
- [Getting Started](#getting-started)  
  - [Clone](#clone)  
  - [Install Dependencies](#install-dependencies)  
  - [Launch Jupyter](#launch-jupyter)  
- [Running in the Cloud](#running-in-the-cloud)  
- [Example Code Snippet](#example-code-snippet)  
- [Contributing](#contributing)  
- [License](#license)  
- [Maintainer / Contact](#maintainer--contact)

---

## About

`Pytorch-QuickBites` is a compact instructional repository intended as a bite-sized daily learning experience for people who want to ramp up on PyTorch quickly. Each notebook presents focused examples and exercises that reinforce one core topic per day.

---





Each notebook is designed to be completed in **30–60 minutes**, serving as a compact but practical daily learning module.

---

## Goal

To help learners quickly become productive with PyTorch by providing:

- Minimal, clean, easy-to-run examples.  
- Progressive learning from tensors → models → training loops → CNNs → RNNs → deployment.  
- Real-world best practices and training workflows.  
- A guided, structured, incremental 12-day curriculum .

---

## Daily Roadmap Overview

> These summaries represent the intended learning flow. You may update them to reflect the exact content inside each notebook.

- **Day 1 — PyTorch Essentials & Tensors**  
  Understanding tensors, operations, shapes, dtypes, broadcasting, and device placement (CPU/GPU).

- **Day 2 — Autograd & Backpropagation**  
  `requires_grad`, computation graphs, `backward()`, gradient inspection, and inference-mode best practices.

- **Day 3 — Neural Network Building Blocks**  
  `nn.Module`, layers (`nn.Linear`, `nn.Conv2d`, etc.), activation functions, `nn.Sequential`, and parameter handling.

- **Day 4 — Training Loop Fundamentals**  
  `Dataset`, `DataLoader`, loss functions, optimizers, manual training & validation loops, checkpointing, and basic experiment tracking.

- **Day 5 — Convolutional Neural Networks (CNNs)**  
  Convolutional layers, pooling, designing a small CNN, and a simple image classification example.

- **Day 6 — Transfer Learning**  
  Loading and adapting pretrained models, freezing vs fine-tuning, and practical tips for transfer learning.

- **Day 7 — Recurrent Networks (RNN / LSTM / GRU)**  
  Sequence data formatting, RNN variants, example sequence task, and batching sequences.

- **Day 8 — Optimization & Regularization**  
  Advanced optimizers, LR schedulers, weight decay, dropout, batch normalization, and stability tricks.

- **Day 9 — Data Pipelines & Augmentation**  
  Custom `Dataset` implementations, `torchvision.transforms`, augmentation strategies, and efficient data loading.

- **Day 10 — Mini Project & Deployment Basics**  
  End-to-end training example, evaluation metrics, simple model export (TorchScript / ONNX), and inference examples.

- **Day 11 — (Optional)** Model Explainability & Visualization  
- **Day 12 — (Optional)** Serving Models (TorchServe, FastAPI, or lightweight deployment)

---

## Requirements

Recommended environment for reproducible execution:

- Python 3.9+  
- PyTorch (CPU or CUDA build, depending on your hardware)  
- Jupyter Notebook / JupyterLab  
- Common supporting libraries: `numpy`, `matplotlib`, `pandas`, `scikit-learn`, `tqdm`  
- `torchvision` (optional — useful for image examples)

Example minimal `requirements.txt`:

```text
torch>=2.0
torchvision>=0.15
numpy
matplotlib
pandas
scikit-learn
tqdm
notebook
jupyterlab

