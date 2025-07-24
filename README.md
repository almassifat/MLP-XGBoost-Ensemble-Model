# MLP-XGBoost-Ensemble-Model
Compare two products using BERT, MLP, and XGBoost ensemble 
This project implements a hybrid deep learning and gradient boosting ensemble model to compare two products and determine which one is better — based on specifications, reviews, and pricing. It combines BERT-based embeddings with traditional machine learning to balance interpretability and accuracy.

📦 Features
🧠 BERT-based review embedding (DistilBERT/BERT-base)

🔢 Tabular features (CPU, GPU, RAM, SSD, Rating, Price)

⚙️ Deep learning (MLP) model + XGBoost ensemble



📈 Performance visualizations and evaluation metrics

🧾 Project Overview
Step	Description
1️⃣	Data analysis, cleaning, normalization

2️⃣	Feature engineering (difference-based)

3️⃣	Text encoding with HuggingFace BERT

4️⃣	Deep learning MLP model

5️⃣	XGBoost classifier

6️⃣	Ensemble using probability averaging

Evaluation: accuracy, precision, recall, F1, AUC, curves


📊 Example Output

Confusion Matrix

Accuracy vs Loss Curve

# 🧠 Model Highlights
Uses BERT to capture semantic meaning from reviews

Custom importance weights for CPU/GPU over display

Ensemble boosts performance beyond individual models

# How To Run:

Clone the repo:

git clone https://github.com/yourusername/MLP-XGBoost-Ensemble-Model.git

cd MLP-XGBoost-Ensemble-Model

Install dependencies:

pip install -r requirements.txt

Open and run the notebook in Colab or locally using Jupyter:

model_training.ipynb

Upload the dataset from Google Drive or update the path in the notebook.


