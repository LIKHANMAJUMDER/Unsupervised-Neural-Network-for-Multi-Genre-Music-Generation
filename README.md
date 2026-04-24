# 🎼 Unsupervised Multi-Genre Music Generation

## 📌 Course
CSE425 / EEE474 — Neural Networks

---

## 🧠 Project Overview

NeuroMuse is an unsupervised deep learning project focused on generating realistic music across multiple genres using symbolic MIDI representations.

Instead of relying on labeled datasets, this project learns the structure of music directly from raw sequences using generative neural models.

The system captures complex musical patterns such as:
- Melody progression
- Rhythm and timing
- Harmony and chord structures
- Genre-specific styles

---

## 🎯 Objectives

- Learn latent representations of music sequences
- Generate new, coherent MIDI compositions
- Compare different generative architectures
- Evaluate musical quality using quantitative and human metrics

---

## 🏗️ Models Implemented

### 🔹 Task 1: LSTM Autoencoder
- Learns compressed representation of single-genre music
- Reconstructs input sequences
- Baseline generative model

### 🔹 Task 2: Variational Autoencoder (VAE)
- Introduces probabilistic latent space
- Enables diverse multi-genre music generation
- Uses KL Divergence for regularization

### 🔹 Task 3: Transformer Generator
- Autoregressive sequence modeling
- Captures long-term dependencies in music
- Generates longer and more coherent compositions

### 🔹 Task 4 (Optional): RLHF Tuning
- Improves generation using human feedback
- Optimizes model using reward-based learning

---

## 📂 Project Structure
