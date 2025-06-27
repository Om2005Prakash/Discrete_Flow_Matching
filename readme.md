# Discrete Flow Matching (Unofficial PyTorch Implementation)

> 🔬 Unofficial implementation of the paper:  
> [**Discrete Flow Matching** (2024)](https://arxiv.org/abs/2407.15595)

<p align="center">
  <img src="./resources/princesspeach.gif" alt="Sampling Process GIF" width="600"/>
</p>

## 📌 Overview

This repository provides an unofficial implementation of **Discrete Flow Matching (DFM)** using **PyTorch** and the **Hugging Face Accelerate** library.  
The model is trained on the **WikiText-103** dataset.

---

## 📈 Results

### Perplexity vs Sampling Steps
<p align="center">
  <img src="./resources/perplexity.png" alt="Perplexity Plot" width="500"/>
</p>

### Entropy vs Sampling Steps
<p align="center">
  <img src="./resources/entropy.png" alt="Entropy Plot" width="500"/>
</p>

---

## 🎥 Additional Sampling Visualizations

<p align="center">
  <img src="./resources/iisc2.gif" alt="Sampling Process GIF 2" width="600"/>
</p>

---

## 🛠️ Setup & Usage

Just run [`dfm_text.ipynb`](./dfm_text.ipynb).