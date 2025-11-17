---
title: "nano_transformers – Building a GPT-style model from scratch"
date: 2025-01-01
hiddenInHomeList: true
type : "Transformers"
---

I built a small **decoder-only transformer (Shakespeare GPT)** from scratch in PyTorch, inspired by Andrej Karpathy’s nanoGPT series.

### Why I built this

There’s only one real way to understand transformers — **implement them yourself**:

- Tokenization
- Embeddings
- Multi-head self-attention
- Residual connections
- Training loop & sampling

### What’s inside the repo

- `bigram.ipynb` – main notebook implementing and training the model
- `train.py` – script to train on a dataset end-to-end
- `inferencing_trained_model.ipynb` – sampling from the trained model and generating Shakespeare-like text

The model was trained on a **Tesla T4 GPU**, and I was able to drive the training loss down to around **0.97**.

### Why it matters

This project shows:

- I understand the internals of **transformers**, not just how to call an API  
- I can read theory, translate it to working code, and diagnose training behaviour  
- I care about doing things the “hard way” at least once to deeply learn them