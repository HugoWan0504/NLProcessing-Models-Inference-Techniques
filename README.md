# Natural Language Processing Models & Inference Techniques

## Overview

This project explores **core Natural Language Processing (NLP) models and inference techniques**, spanning both classical distributional semantics and modern deep learning–based approaches. The work focuses on how textual meaning is represented, transformed, and generated using neural architectures.

Two complementary components are implemented:

1. **Distributional word representation learning**
2. **Transformer-based sequence-to-sequence modeling for machine translation**

---

## Part I: Distributional Word Embeddings

### Description

This component implements **Skip-Gram with Negative Sampling (SGNS)** to learn dense vector representations of words from raw text. The model captures semantic relationships by optimizing word–context co-occurrence statistics.

### Key Techniques

* Subword-aware tokenization using **Byte Pair Encoding (BPE)**
* Skip-Gram objective with **negative sampling**
* Analysis of embedding quality via semantic similarity

---

## Part II: Transformer-Based Machine Translation

### Description

This component implements a **Transformer-based encoder–decoder architecture** for neural machine translation. The model leverages **self-attention mechanisms** to capture long-range dependencies in language.

### Key Techniques

* Multi-head self-attention and positional encoding
* Encoder–decoder Transformer architecture
* **Sequence decoding strategies**, including **Greedy decoding** and **Beam Search**
* Language model fine-tuning using **REINFORCE**
* Efficiency-oriented methods such as **knowledge distillation, pruning, and LoRA**

---

## Core NLP Concepts Demonstrated

* Distributional semantics and representation learning
* Tokenization and vocabulary construction
* Attention-based neural architectures
* Probabilistic sequence modeling and decoding
* Efficiency and scalability considerations in NLP models

---

## Implementation Details

* Implemented in **Python**
* Neural models built using modern deep learning frameworks
* Modular notebook-based structure for clarity and experimentation
* Emphasis on correctness, interpretability, and reproducibility

---

## Repository Structure

* `Skip_Gram_Model.ipynb`
  Implementation and analysis of Skip-Gram with Negative Sampling
* `Transformer_Machine_Translation.ipynb`
  Transformer-based machine translation with multiple decoding strategies

---

## Project Status

* All models implemented and validated
* Experimental results analyzed and documented
* No known functional issues

---

## Author

**Hugo Wan**

---

## Notes

This project demonstrates a progression from **classical NLP foundations** to **modern Transformer-based models**, highlighting practical skills applicable to **language modeling, machine translation, and large-scale NLP systems**.
