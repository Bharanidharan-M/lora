## LoRA Fine-Tuning of Falcon-RW-1B on Indian Film Q&A Dataset

This project demonstrates how to fine-tune the `tiiuae/falcon-rw-1b` model using Parameter-Efficient Fine-Tuning (PEFT) via LoRA on a small Q&A dataset related to Indian cinema. The goal is to adapt a large language model efficiently with minimal compute resources.

## 📦 Dependencies

Install all required packages using pip:

```bash
pip install -q transformers datasets peft accelerate bitsandbytes
