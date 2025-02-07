# GreenAI LLaMA Fine-Tuning with LoRA Optimization

This project demonstrates fine-tuning a LLaMA-based model using Low-Rank Adaptation (LoRA) with 4-bit quantization to reduce computational resource consumption and environmental impact. The project was developed as part of the Vector Institute GreenAI Bootcamp, focusing on creating efficient, low-cost, and environmentally sustainable fine-tuning methods for large language models. By integrating LoRA for efficient updates and quantization techniques to reduce memory usage, this project shows that fine-tuning can be performed on low-resource machines without compromising performance. Carbon emissions from training and inference are also tracked using the CodeCarbon library.

Key aspects of the project include:
- LoRA-based fine-tuning, which applies low-rank decomposition to large language models, significantly reducing the number of trainable parameters while maintaining performance.
- 4-bit quantization to minimize GPU memory consumption and allow fine-tuning on resource-constrained systems like Colab.
- Carbon emissions monitoring using CodeCarbon, tracking and reporting the environmental impact of both training and inference.
- Efficient loading and saving of model checkpoints for future use and inference on new instructions.

## Installation Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/alishaarora56/greenai-lora-llama-finetune.git
   cd greenai-lora-llama-finetune

# 
This project implements LoRA, a method for low-rank adaptation described in Hu et al. (2021).
Hu, Edward J., et al. LoRA: Low-Rank Adaptation of Large Language Models (2021). https://arxiv.org/abs/2106.09685

Additionally, the project is built on the LLaMA architecture for efficient large language model training and inference. LLaMA details can be found at: Gerganov, Georgi. LLaMA.cpp: Efficient LLaMA Inference (GitHub Repository). https://github.com/ggerganov/llama.cpp
