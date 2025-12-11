# sentiment-analysis-IMBD
End-to-end sentiment analysis pipeline using TF-IDF + Logistic Regression with IMDB dataset, calibration, and rich visualizations

readme = f"""# Sentiment Analysis on IMDB (Baseline + Rich Evaluation)

![Build](https
![icense

## Overview
End-to-end **NLP sentiment analysis** on the IMDB Large Movie Review Dataset using a **TF–IDF + Logistic Regression** baseline, with rich evaluation and visualizations:
- **Discrimination:** ROC/PR curves, ROC-AUC, PR-AUC
- **Calibration:** Reliability diagram, **ECE**, **Brier score**
- **Confusion matrices:** raw & normalized
- **Probability histograms:** per true class
- **Threshold search:** F1 vs threshold on validation
- **Explainability:** top positive/negative TF–IDF features
- **Error analysis:** most confident misclassifications

Colab-ready: a single notebook/script downloads data, trains, evaluates, visualizes, and pushes results.

## Dataset
- Official page: http://ai.stanford.edu/~amaas/data/sentiment/
- Direct download: https://ai.stanford.edu/~amaas/data/sentiment/aclImdb_v1.tar.gz
- Citation:

