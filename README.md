# SVD_and_NMF_Analysis_on_different_datasets

# SVD vs NMF: A Comparative Study Across Multiple Data Modalities

This repository contains the **official Python implementation and experimental analysis**
supporting the paper:

> **“SVD and NMF Comparison on Different Datasets”**  
> University of Colorado Boulder — APPM Assignment  
> Instructor: Prof. James H. Curry

The project presents a **systematic comparison of Singular Value Decomposition (SVD)**
and **Non-Negative Matrix Factorization (NMF)** across **multiple real-world and synthetic
datasets**, evaluating reconstruction accuracy, interpretability, and domain suitability.

---

## 📌 Project Motivation

Matrix factorization techniques such as **SVD** and **NMF** are widely used for:
- Dimensionality reduction
- Signal reconstruction
- Feature extraction
- Compression

However, their performance and interpretability vary significantly depending on:
- Data modality
- Presence of non-negativity constraints
- Noise and structure in the data

This project explores **where each method works best** by applying them to:
- Chaotic dynamical systems
- Real Wi-Fi time-series data
- Image data
- Audio signals

---

## 🎯 Objectives

- Compare **SVD and NMF** across heterogeneous datasets
- Quantify reconstruction performance using **MSE, MAE, and Frobenius norm**
- Analyze **rank-based trade-offs** between accuracy and interpretability
- Understand the impact of **non-negativity constraints**
- Demonstrate **Singular Spectrum Analysis (SSA)** for time-series decomposition

---

## 📂 Repository Structure

```text
.
├── logistic_nap_svd_nmf_along_with_wifidata.ipynb
│   ├── Logistic map generation
│   ├── SSA via Hankel matrix embedding
│   ├── Wi-Fi time-series decomposition (SVD vs NMF)
│   ├── Image compression (Pumpkin image)
│
├── music.ipynb
│   ├── Audio → time-series conversion
│   ├── SVD and NMF reconstruction on music data
│
└── README.md
