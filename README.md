# 🚀 LLM Foundations & Architecture Research

## 📌 Overview

This repository documents my foundational learning and technical exploration of Large Language Models (LLMs). As a Computer Science student at BRAC University, this repository serves as the central hub for my research.

My primary objective is to deeply understand the underlying architecture of LLMs (how they are built, trained, and generate responses) to effectively bridge the gap between core mechanics and security flaws.

## 📺 Current Learning Material

- **Currently Watching:** [How LLMs Works? - Overview by Piyush Garg](https://www.youtube.com/watch?v=K45s2PgywvI&t=1158s)

---

## 🛠️ Environment Setup

To replicate this research environment and run the LLM scripts, ensure you have **Python 3.8+** installed. Use the following commands in your terminal:

### 1. Install/Upgrade Transformers

This library from Hugging Face is the industry standard for working with pre-trained LLMs and Tokenizers.

```bash
pip3 install --upgrade transformers
```

### 2. Install PyTorch (The Core Engine)

PyTorch handles the heavy mathematical lifting (Tensors and Matrix Multiplications) required for Vector Embeddings.

```Bash
pip3 install torch torchvision
```

## 🧠 Core Concepts Mastered (Progress Tracker)

### 1. The Transformer Architecture

- **Generative Pre-trained Transformers (GPT):** Understanding how models generate text based on next-word prediction sequences using pre-trained data [00:01:56].
- **Encoding & Decoding:** The process of feeding input sequences into the model and decoding the output predictions.

### 2. Tokenization

- Breaking down human-readable text (words, sub-words, or characters) into numerical values that a computer can process [00:11:04].
- Understanding that tokenization algorithms and vocabulary sizes vary across different models (e.g., GPT-4 vs. Gemini).

### 3. Vector Embeddings

- Representing tokens as dense numerical vectors in a multi-dimensional space to capture semantic relationships [00:17:54].
- Mapping words so that semantically similar concepts (e.g., "cat" and "dog") are plotted closer together in the vector space, allowing the model to understand real-world context.

## 🗺️ Future Roadmap

As I progress toward Summer 2026, this repository will be updated with code snippets, architectural diagrams, and notes on the following topics:

- [ ] **Positional Encoding:** Understanding how models keep track of the order of words in a sentence.
- [ ] **Attention Mechanisms:** Exploring Self-Attention and Multi-Head Attention to see how models maintain context over long sequences.
- [ ] **Training vs. Inference:** The mathematical differences between updating model weights (Backpropagation) and generating live text.
- [ ] **Fine-Tuning:** How to adapt base models for specific use cases.
- [ ] **LLM Security Integrations:** Analyzing where vulnerabilities (like prompt injection or data poisoning) interact with the core architecture.

## 👨‍💻 Author

**Prantik** _Computer Science, BRAC University_
[will be updated]
