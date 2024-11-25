
# **.Further-Pretrained Spritual-BERT

### 1. Pre-Training with MLM
- Loads the `bert-base-uncased` model and tokenizer.
- Prepares text data for masked language modeling.
- Trains the model for a specified number of epochs with dynamic masking applied to tokens.

### 2. Fine-Tuning
- Processes labeled datasets for multi-label classification tasks.
- Fine-tunes the Spiritual BERT model on spiritual care categories like:
  - **Spiritual**,
  - **Existential**,
  - **Religious**, and
  - **Values**.
  
# **.Spiritual Care Multi-Label Classification

This repository provides a workflow for fine-tuning, evaluating, and visualizing machine learning models for multi-label classification in a spiritual care dataset. The workflow includes processing data, training models, computing evaluation metrics, and generating visualizations.

---

## Features

1. **Fine-Tuning Models**:
   - Loops through multiple pre-trained models and fine-tunes them for spiritual care classification.
   - Saves fine-tuned models and evaluation metrics.

2. **Evaluation**:
   - Computes metrics such as precision, recall, F1-score, AUC, and AUPRC for both test and external validation datasets.
   - Supports multi-label classification with flexible dataset processing.

3. **Visualization**:
   - Generates ROC curves for individual labels.
   - Creates averaged ROC curves across all labels for better model comparison.

