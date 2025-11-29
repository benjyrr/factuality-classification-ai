# Detecting Factuality in AI-Generated Educational Content

This project was developed for the **Data4Good 2025 Competition**, which challenged participants to classify AI-generated educational answers as *Factual*, *Contradiction*, or *Irrelevant*.

## 🧠 Overview
- Built baseline **TF-IDF + Logistic Regression** model with engineered overlap and negation features.
- Fine-tuned **DistilRoBERTa transformer**, improving macro-F1 from **0.78 → 0.92** and accuracy from **0.91 → 0.97**.
- Conducted error and confusion matrix analyses to evaluate class performance and contextual reasoning.

## 📊 Results
| Metric | Baseline | Transformer | Gain |
|---------|-----------|--------------|------|
| Macro F1 | 0.78 | 0.92 | +0.14 |
| Accuracy | 0.91 | 0.97 | +0.06 |

## 🛠️ Tech Stack
Python • scikit-learn • Transformers (Hugging Face) • Pandas • Matplotlib

## 📂 Files
- `notebook.ipynb` — Full analysis and training pipeline.
- `outputs/predictions.json` — Final competition submission.
- `outputs/predictions_baseline.json` — Baseline model predictions.

## 🏁 Outcome
Achieved top-tier performance and documented a fully reproducible NLP workflow focused on factual accuracy and interpretability.
