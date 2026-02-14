![GitHub streak stats](https://github-readme-streak-stats.herokuapp.com/?user=ehsanulimon) 

# 📊 Bangla Drama and TV Series Sentiment Analysis

This repository contains the source code, dataset link, and models used in our research paper:

🎓 **Title**: *Analyzing Bangla Drama and TV Series Reviews Using Stacking Method*  
📚 **Published in**: ACM Digital Library (ICCA 2024)  
🔗 [Read the Paper](https://dl.acm.org/doi/10.1145/3723178.3723186)

## 📌 Abstract

Sentiment analysis of entertainment reviews is widely studied in English and other languages, but Bangla is often neglected.  
This study presents the first large-scale Bangla sentiment analysis dataset containing **20,000 reviews** from 93 dramas and 28 TV series.

We applied multiple Machine Learning and Deep Learning models (SVM, CNN-GRU) and proposed a **Stacking Ensemble Model**, which achieved:

✅ **Accuracy**: 82.95%  
✅ **Best Model**: CNN-GRU + Meta-learner  
✅ **Explainability**: LIME & SHAP used for model interpretation

## 🗃 Dataset

Available on GitHub:  
🔗 [Bangla Drama Review Dataset](https://github.com/cseku170202/Bangla-Drama-and-TV-Series-Sentiment-Analysis)

- Total Samples: 20,000
- Labels: Positive / Negative
- Source: YouTube Comments

## 🛠 Models

- Classical ML: Naïve Bayes, SVM, Logistic Regression, RF ,KNN
- Deep Learning: CNN, RNN, GRU, LSTM, Bi-LSTM, Bi-GRU, CNN-GRU, CNN-LSTM, CNN-BiGRU, CNN-BiLSTM.
- Ensemble: Stacking (10 DL Models + Meta-Learner)

## 📈 Results

| Model       | Accuracy | F1-Score |
|-------------|----------|----------|
| SVM         | 73.28%   | 0.732    |
| CNN-GRU     | 79.83%   | 0.798    |
| **Stacking**| **82.95%** | **0.825** |

## 📊 Explainability

- 🔍 Local: **LIME** highlights key words per prediction
- 🔍 Global: **SHAP** for feature impact visualization
