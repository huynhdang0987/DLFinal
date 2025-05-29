# 🧠 Deep Learning Final Project

**Course**: Deep Learning  
**Instructor**: [PGS.TS Le Anh Cuong]  
**Team Members**: [Huynh Dang Khoa - 522H0104, Chau Bao Nhan - 522H0093, Le Hai Dang - 522H0112]

---

## 📌 Overview

This repository contains the final project submission for the Deep Learning course. The project is divided into **two parts**:

1. **Advanced Study of Attention Mechanisms in LLMs**
2. **Image-to-Text Extraction using CNN + Transformer Decoder**

---

## 🧠 Part 1: Advanced Attention Mechanisms in LLMs

### 🎯 Objective

- Study, implement, and compare **modern attention mechanisms** used in large language models (LLMs).
- Provide theoretical explanations and PyTorch implementations with visualizations.

### ✅ Selected Attention Mechanisms

- Self-Attention (baseline)
- Multi-Query Attention (MQA)
- Grouped-Query Attention (GQA)
- FlashAttention v2
- Linear Attention
- Rotary Positional Embedding (RoPE)

### 📚 Content

- Theoretical explanation:
  - Core idea and working mechanism
  - Computational complexity
  - Pros and cons
  - Comparison with vanilla Self-Attention
  - Real-world applications in LLMs (e.g., GPT, LLaMA)
- PyTorch implementation for each attention mechanism as a reusable module
- Simple input example and printed attention matrix


## 🖼️ Part 2: OCR using CNN + Transformer Decoder

### 🎯 Objective

- Build an OCR (Optical Character Recognition) system **from scratch** using a CNN as encoder and Transformer Decoder as sequence generator.
- No prebuilt OCR models (e.g., EasyOCR, TrOCR) were used.

### 🏗️ Architecture

- **CNN Backbone** (e.g., ResNet): Extracts image features.
- **Transformer Decoder**: Generates output text sequence from features.
- **Cross-Attention**: Allows decoder to focus on image regions while decoding characters.

### 📷 Dataset

Real world dataset CCCD on Kaggle. Here is the link: https://www.kaggle.com/datasets/tdmquan77/cccd-dataset

### 📊 Evaluation & Visualization

- Text prediction accuracy on the test set.
- Visual output includes:
  - Original input image
  - Predicted text
  - Attention heatmap (optional)
We have deploy the model on to the website. Here are example:
![Input Example](https://github.com/huynhdang0987/DLFinal/blob/main/cccd.jpg)

