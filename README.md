# 📌 iQoERec

This repository contains the official implementation (**to be released**) of the paper:

> **Balancing User Experience and Monetization: An iQoE-Aware Recommendation Framework for Audio Platforms**

---

## 📖 Overview

Modern recommendation systems often face a fundamental trade-off between:

- **User Experience**
- **Monetization (e.g., payment/conversion)**

This project introduces **iQoE (Instantaneous Quality of Experience)** as a fine-grained, dynamic representation of user experience, and proposes a unified framework to jointly optimize both objectives.

---

## 🚀 Key Features

- **iQoE Modeling**  
  Explicitly models real-time user experience during interaction.

- **Multi-Objective Learning**  
  Jointly optimizes:
  - Pay (monetization behavior)
  - iQoE (experience quality)

- **Multi-Expert Architecture (MMoE-based)**  
  - Shared + task-specific experts  
  - Gating mechanism to reduce task interference  

- **Dynamic Loss Balancing**  
  - Automatically adjusts task weights based on uncertainty  

- **Multi-Objective Re-ranking**  
  - PRS (Preference Ranking Strategy)  
  - WRS (Weighted Ranking Strategy)  
  - SRS (Segment Ranking Strategy, best performing)

---

## 🧠 Framework Overview

The proposed framework consists of:

1. Feature Embedding Layer  
2. Shared Encoder  
3. Multi-gate Mixture-of-Experts (MMoE)  
4. Task-specific Towers (Pay & iQoE)  
5. Dynamic Loss Adjustment  
6. Re-ranking Module (Top-K Optimization)  

---

## 📂 Dataset

The experiments are conducted on **real-world datasets from a large-scale interactive audio platform**.

Due to privacy restrictions, the dataset is currently **not publicly available**.

Possible future releases may include:
- Data schema  
- Simulation or preprocessing tools  

---

## 🔄 Roadmap

- [ ] Release model implementation  
- [ ] Provide training scripts  
- [ ] Add demo or example pipeline  
- [ ] Release synthetic dataset or preprocessing tools  

---

## ⚖️ License

This project is licensed under the MIT License.
