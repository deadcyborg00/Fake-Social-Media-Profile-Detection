# Fake-Social-Media-Profile-Detection
*Dayananda Sagar University, Dept. of CSE (Cyber Security)*  

---

## 📖 Project Overview

Social media platforms are plagued by fake profiles—bots or malicious users that impersonate real accounts to spread misinformation, execute scams, and erode trust.  
This repository implements an AI‑powered detection framework combining:

- **Structured features** (e.g. follower/following ratios, post frequency, engagement metrics)  
- **Unstructured text analysis** (profile bios & post captions via NLP)  
- **Deep learning & synthetic data** (GAN‑generated fake profiles)  
- **Dimensionality reduction** (PCA, LDA/MDA)  

The result is a scalable, adaptable system that flags suspicious accounts with high accuracy, recall, and precision.

---

## 🚀 Features

- **Data Collection & Augmentation**  
  - Scrape public profiles using Instaloader & OSINTgram  
  - Use GANs to generate synthetic fake‐profile samples  
- **Feature Engineering**  
  - Behavioral: posting frequency, network topology, engagement ratios  
  - Textual: NLP‐extracted embeddings from bios & captions  
- **Dimensionality Reduction**  
  - Principal Component Analysis (PCA)  
  - Multiple/Linear Discriminant Analysis (MDA/LDA)  
- **Model Zoo**  
  - Traditional ML: Logistic Regression, SVM, Naïve Bayes, Random Forest, XGBoost, LightGBM  
  - Deep Learning: ANN, CNN  
- **Evaluation**  
  - Cross‐validation; metrics: accuracy, precision, recall, F1‑score, ROC‑AUC, PR‑AUC, MCC  
- **Ethical & Scalable**  
  - Privacy‐preserving (only public data)  
  - Adaptable to new tactics via continuous retraining  

---



