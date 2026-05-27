# IndustryGPT: Retail E-commerce Customer Support Bot

This repository contains the Colab notebook for the AlmaBetter capstone project **IndustryGPT: Specialized LLM Bot Using Pre-Trained Models**.

## Project Overview

The project builds a retail and e-commerce customer support chatbot using a pre-trained Hugging Face LLM. The notebook fine-tunes `Qwen/Qwen2.5-3B-Instruct` with QLoRA 4-bit on customer-support data and saves the trained LoRA adapter to Google Drive.

## Notebook

Open this notebook in Google Colab:

```text
Retail E-commerce_Qwen25_3B_QLoRA_Customer_Support_Bot.ipynb
```

## Main Features

- Retail and e-commerce customer support use case
- Dataset loading and inspection
- Data cleaning and preprocessing
- Qwen2.5 3B Instruct model selection
- QLoRA 4-bit fine-tuning
- Google Drive model adapter saving
- Base model vs fine-tuned model comparison
- Gradio chatbot interface for live demo

## Reuse After Training

After the notebook is fully trained once and the LoRA adapter is saved in Google Drive, training does not need to be repeated. For later demos, run only the setup, adapter loading, and Gradio UI cells mentioned inside the notebook.

## Note

The trained LoRA adapter and checkpoints are saved in Google Drive, not in this GitHub repository, because model artifacts can be large. The notebook contains the complete workflow needed to train, save, load, evaluate, and demonstrate the chatbot.
