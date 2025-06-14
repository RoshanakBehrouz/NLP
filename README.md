# NLP
Natural Language Processing
# NLP Final Project

This project explores the **comparative evaluation of Encoder-Only and Decoder-Only Transformer models** for sentiment analysis using the IMDb dataset. Lightweight implementations have been developed from scratch using PyTorch, avoiding pre-trained models.

## Project Description

The primary goal of this project is to analyze the structural and performance differences between:
- **Encoder-Only models** (BERT-style)
- **Decoder-Only models** (GPT-style)

All models are trained **from scratch** with:
- Reduced embedding size (`d_model=256`)
- Fewer layers and attention heads
- Supervised training for binary classification

This makes training feasible in constrained environments such as Google Colab.

## Features

- Custom dataset handling
- Lightweight Transformer implementations
- Comparative training and evaluation
- Visualization of performance metrics (accuracy, loss, confusion matrix, etc.)

## Requirements

```bash
torch
transformers
scikit-learn
matplotlib
seaborn
pandas
```

## Running the Notebook

1. Open `NLP_Final.ipynb` in Jupyter or Google Colab.
2. Run each cell in order.
3. The dataset is loaded from Hugging Face using the `datasets` library.

## Results Summary

The notebook provides:
- Accuracy scores
- Training loss plots
- Confusion matrices
- Comparative analysis of both model types

## Visualizations

- Accuracy/Loss curves for both models
- Attention heatmaps (if any)
- Confusion matrices

## Authors

Roshanak Behrouz  
University of Trieste, Master's in Data Science & AI

---

> **Note:** The models are designed for educational experimentation and not for production use.

