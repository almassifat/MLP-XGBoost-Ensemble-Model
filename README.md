# 🚀 MLP + XGBoost Ensemble Model for Product Comparison

[![Python](https://img.shields.io/badge/Python-3.9-blue.svg)]()
[![PyTorch](https://img.shields.io/badge/Framework-PyTorch-orange.svg)]()
[![XGBoost](https://img.shields.io/badge/Model-XGBoost-green.svg)]()
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)]()

---

## 📝 Overview

This project implements a **hybrid deep learning + gradient boosting ensemble model** to compare **two products** and determine which one is better.  
It leverages **BERT-based embeddings** for textual reviews, combines them with **tabular features**, and uses a **Multi-Layer Perceptron (MLP)** along with **XGBoost** to achieve **high interpretability and accuracy**.

---

## ✨ Features

- 🧠 **BERT-based review embeddings** (DistilBERT / BERT-base)  
- 🔢 **Tabular features:** CPU, GPU, RAM, SSD, Rating, Price  
- ⚙️ **MLP deep learning model** + **XGBoost ensemble**  
- 📈 **Performance visualizations** (confusion matrix, loss & accuracy curves)  
- 🧮 **Explainability:** Feature importance & SHAP values  

---

## 🧾 Project Pipeline

| Step | Description |
|------|-------------|
| 1️⃣ | Data analysis, cleaning, normalization |
| 2️⃣ | Feature engineering (difference-based numerical features) |
| 3️⃣ | Text encoding using HuggingFace **BERT** |
| 4️⃣ | Deep learning **MLP** model for numeric features |
| 5️⃣ | **XGBoost** classifier for structured data |
| 6️⃣ | Ensemble via **probability averaging** for final decision |
| ✅ | Evaluation using accuracy, precision, recall, F1, AUC, and visualization plots |

---

## 🧠 Model Highlights

- ✍️ **Semantic understanding** of reviews using BERT  
- 🎯 **Custom importance weighting** (CPU/GPU emphasized over display features)  
- 🔗 **Ensemble learning** improves performance over individual models  
- 📊 **Explainable AI:** Feature importance and SHAP analysis for decision reasoning  

---



## ⚡ Installation

```bash
git clone https://github.com/yourusername/MLP-XGBoost-Ensemble-Model.git
cd MLP-XGBoost-Ensemble-Model
pip install -r requirements.txt
