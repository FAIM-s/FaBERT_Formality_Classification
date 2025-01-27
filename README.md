# Fabert_Formality_Classifier
This repository includes notebooks for finetuning FaBERT model in formality detection task and how to get inference from finetuned model

# Fabert Formality Classifier

[![View on Hugging Face](https://img.shields.io/badge/Hugging%20Face-Model%20Page-yellow)](https://huggingface.co/FAIMs/fabert_formality_classifier/tree/main)

[View on Hugging Face](https://huggingface.co/FAIMs/fabert_formality_classifier/tree/main).

Fabert Formality Classifier is a pre-trained model designed to classify the formality level of text. This model can be used in applications like sentiment analysis, content moderation, academic writing assistance, and more.

## Features

- **Accurate Classification:** Determines the formality level of text (formal or informal).
- **Easy Integration:** Compatible with Hugging Face libraries for seamless integration.
- **Customizable:** Can be fine-tuned for domain-specific applications.

## Installation

To use the model, you need the `transformers` library from Hugging Face. You can install it via pip:

```bash
pip install transformers
```

## Usage

Here's a quick example of how to load and use the model:

```python
from transformers import AutoTokenizer, AutoModelForSequenceClassification

# Load tokenizer and model
tokenizer = AutoTokenizer.from_pretrained("FAIMs/fabert_formality_classifier")
model = AutoModelForSequenceClassification.from_pretrained("FAIMs/fabert_formality_classifier")

```

## Contributions

Contributions to improve the model or its documentation are welcome. Please feel free to open an issue or submit a pull request on the corresponding repository.

---
