# Fairness in Multilingual Sentiment Analysis: A Comparative Study of BERT, DistilBERT, and XLM-RoBERTa

This repository contains all notebooks, models(and weights), and analysis used to evaluate the fairness of multilingual sentiment classifiers, focusing on DistilBERT, BERT, and XLM-RoBERTa models. The goal was to analyze both performance and fairness trade-offs when training models on all languages versus fine-tuning them individually. Additionally, we are also exploring majority-voting as a potential solution to improving fairness.

All results and findings are discussed in detail in the accompanying report.

## Structure

- `Clotan Notebooks`: Training and evaluation for the Spanish model and DistilBERT-specific experiments.
- `Izvoreanu Notebooks`: Training and evaluation for the German model and XLM-RoBERTa.
- `Gravina Notebooks`: Training and evaluation for the English model and BERT.
- `Models weights`: Pretrained and fine-tuned model weights.
- `Data Analysis.ipynb`: Common preprocessing pipeline used across all runs.
- `ethics-distilbert-training.ipynb` and `model-evaluation.ipynb`: Central notebooks for DistilBERT training and metric reporting.

## Platform

All experiments were conducted on **Kaggle**. We recommend running the notebooks directly on Kaggle for compatibility and reproducibility.

---

For further details, model comparisons, metric definitions, and conclusions, please refer to the full report.
