# Nano GPT

A character-level GPT (Generative Pre-trained Transformer) language model trained on the Tiny Shakespeare dataset. 

This repository contains the companion notebook developed while following Andrej Karpathy's "Neural Networks: Zero to Hero" series. It demonstrates the fundamental architecture and training loop of a decoder-only transformer model from scratch.

## Project Structure
* `gpt_dev.ipynb`: The main Google Colab notebook containing the model architecture, data processing, and training pipeline.

## Dataset
The model is trained on the **Tiny Shakespeare** dataset, which concatenates all of Shakespeare's works into a single text file (approx. 1MB). The model learns to predict the next character in a sequence, effectively generating Shakespeare-like text after training.

## Getting Started

To explore or run the code:
1. Open `gpt_dev.ipynb` directly in GitHub.
2. Click the **Open in Colab** badge at the top of the file to launch it in Google Colab.
3. Run the cells sequentially to download the dataset, initialize the model, and begin training.

Alternatively, to run it locally:
```bash
git clone [https://github.com/gehanimitali14feb-spec/nano_gpt.git](https://github.com/gehanimitali14feb-spec/nano_gpt.git)
cd nano_gpt
