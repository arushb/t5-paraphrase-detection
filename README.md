# T5 Paraphrase Detection

This project fine-tunes the **T5 transformer model** on the **GLUE MRPC dataset** to perform **paraphrase detection** — determining whether two sentences have the same meaning.

## Features
- Uses the **Hugging Face Transformers** library with **T5-small**
- Loads and processes the **MRPC dataset** from **GLUE benchmark**
- Custom preprocessing to tokenize sentence pairs and label them as "equivalent" or "not equivalent"
- Evaluates model performance using **accuracy** and **F1-score**

## Tech Stack
- **Python**
- **PyTorch**
- **Hugging Face Transformers**
- **Datasets (GLUE MRPC)**
- **scikit-learn**

## Setup
```bash
pip install transformers datasets torch scikit-learn sentencepiece
