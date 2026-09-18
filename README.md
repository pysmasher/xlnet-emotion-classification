# Fine-Tuning XLNet for Emotion Classification

## Overview

Fine-tuned a pre-trained XLNet Transformer model on a custom emotion dataset to classify text into four emotion categories: joy, anger, fear, and sadness.

## Workflow

```text
Custom Emotion Dataset
        ↓
Text Preprocessing
        ↓
XLNet Tokenization
        ↓
Train / Validation Split
        ↓
XLNet Fine-Tuning
        ↓
Model Evaluation
        ↓
Text Classification Inference
```

## Technologies

* Python
* PyTorch
* Hugging Face Transformers
* XLNet
* NLP
* Text Classification
* Fine-Tuning
* Tokenization

## Model

Pre-trained model:

```text
xlnet-base-cased
```

## Classes

```text
Joy
Anger
Fear
Sadness
```

## Training

The model was fine-tuned for 3 epochs.

## Result

* Training Loss: 1.359
* Evaluation Loss: 1.376
* Accuracy: 39%

## Inference

The fine-tuned model was saved and loaded using Hugging Face Transformers for text classification inference.

Example:

```python
classifier("I am extremely happy today!")
```

## Project Structure

```text
notebooks/
└── xlnet_emotion_classification.ipynb

README.md
requirements.txt
.gitignore
```
