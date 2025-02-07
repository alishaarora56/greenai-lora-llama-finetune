# 🌱 GreenAI LLaMA Fine-Tuning with LoRA Optimization

This project demonstrates fine-tuning a **LLaMA-based model** using **LoRA (Low-Rank Adaptation)** with **4-bit quantization** to reduce computational resource consumption and environmental impact. The work was developed as part of the **GreenAI Bootcamp** to explore efficient, low-cost fine-tuning of large language models while tracking and minimizing **carbon emissions** during training and inference.

---

##  Project Overview

With the growing concerns about the **energy efficiency** of large-scale AI models, this project integrates **LLaMA fine-tuning** with **LoRA** techniques and **quantization optimizations** to improve training speed and memory efficiency. Specifically, the project uses **LoRA for efficient weight updates** and **4-bit quantization** for memory reduction, making fine-tuning feasible on lower-resource machines, such as GPUs available in Google Colab.

---

###  Key Features:
- **LoRA-based Fine-Tuning:** Efficient low-rank updates to large models, inspired by the method described in [Hu et al. (2021)](https://arxiv.org/abs/2106.09685).
- **4-Bit Quantization:** Reducing memory usage without significantly compromising model performance.
- **Carbon Emissions Tracking:** Integrating `codecarbon` to monitor and report the environmental impact of model training and inference.
- **Inference with Optimized Checkpoints:** Model checkpoint saving and loading for fast and efficient evaluation.

---

## 🛠️ Installation Instructions

 **Clone the repository:**
   ```bash
   git clone https://github.com/alishaarora56/greenai-lora-llama-finetune.git
   cd greenai-lora-llama-finetune
