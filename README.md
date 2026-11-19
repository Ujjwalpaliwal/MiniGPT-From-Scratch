# MiniGPT From Scratch

A small character-level GPT language model implemented from scratch using PyTorch.

## Project Overview

This project demonstrates the core architecture of a GPT-style language model. It covers tokenization, embeddings, causal self-attention, multi-head attention, Transformer blocks, model training, evaluation, and autoregressive text generation.

The complete implementation was developed in Google Colab using PyTorch.

## Architecture

The model follows this pipeline:

1. Character-level Tokenization
2. Token and Positional Embeddings
3. Causal Self-Attention
4. Multi-Head Attention
5. Transformer Blocks
6. Final Layer Normalization
7. Language Modeling Head
8. Autoregressive Text Generation

## Model Configuration

| Parameter | Value |
|---|---:|
| Embedding Dimension | 32 |
| Attention Heads | 4 |
| Transformer Blocks | 4 |
| Context Length | 16 |
| Dropout | 0.1 |
| Vocabulary Size | 38 |

## Training Results

| Metric | Result |
|---|---:|
| Training Loss | 2.6934 |
| Validation Loss | 2.7111 |
| Training Time | 34.8 seconds |

## Technologies

- Python
- PyTorch
- NumPy
- Matplotlib
- Google Colab

## Repository Structure

```text
MiniGPT-From-Scratch/
├── README.md
├── requirements.txt
├── MiniGPT_From_Scratch.ipynb
└── .gitignore
```

## How to Run

1. Download the notebook from this repository.
2. Open [Google Colab](https://colab.research.google.com/).
3. Upload the `.ipynb` notebook.
4. Select Runtime and run the notebook cells sequentially.

## Limitations

This is a small educational character-level language model. It learns basic character patterns but does not produce consistently coherent or contextually meaningful text.

## Future Improvements

- Train on a larger dataset.
- Increase context length and model dimensions.
- Experiment with optimization and sampling strategies.
- Improve evaluation and generation quality.

## Author

Ujjwal Paliwal

Developed as a hands-on learning project to understand GPT and Transformer architecture from scratch.