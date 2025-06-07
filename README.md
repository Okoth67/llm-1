 🧠 LLM Engineering - Preparing GPT-2 for Classification: Data Loading, Tokenization, and Model Setup

This repository documents my weekly hands-on learning as I build practical skills in Natural Language Processing (NLP) and Large Language Models (LLMs), focusing on preparing and fine-tuning GPT-2 models.

📂 Projects This Week
Initializing GPT-2 for Sequence Classification
File: run_classifier.py

Loaded the IMDb dataset and prepared sample text-label pairs

Initialized GPT-2 with a sequence classification head (GPT2ForSequenceClassification) for binary sentiment classification

Built a PyTorch Dataset class and DataLoader to tokenize and batch the text inputs

Set up the training loop skeleton with optimizer and scheduler — training not yet performed

Implemented a basic inference method to test model outputs on sample inputs
This work lays the groundwork to fine-tune GPT-2 on classification tasks by adapting its architecture and preparing data pipelines.

Notebook: dataloader.ipynb
Practiced creating custom PyTorch datasets and dataloaders for text data, focusing on tokenization and padding — critical for efficient batch processing.

Notebook: downloading_and_processing_dataset.ipynb
Explored loading datasets using Hugging Face datasets library and preparing raw text for tokenization. Proper data preparation ensures models receive well-formatted inputs.

Notebook: gpt2.ipynb
Investigated GPT-2 tokenizer behavior and model loading to understand tokenization mechanics and model architecture.

Notebook: saving_loading_weights.ipynb
Learned saving and loading PyTorch model weights using torch.save() and load_state_dict(), foundational for checkpointing models during training.

Notebook: loading_and_saving_openai_weights.ipynb
Experimented with loading OpenAI GPT model weights into Hugging Face’s GPT-2 format and saving them, expanding compatibility between model formats.

Notebook: initializing_model_for_finetuning.ipynb
Focused on preparing pretrained GPT-2 models for downstream tasks by adding classification heads and configuring tokenizers (e.g., setting pad tokens).

🛠️ Tech Stack
Python

PyTorch

Hugging Face Transformers & Datasets

Jupyter Notebooks

Git & GitHub

📚 Learning Goals
Understand dataset loading and preprocessing for NLP

Prepare and tokenize text inputs for GPT-2 fine-tuning

Initialize GPT-2 with classification heads suitable for sentiment analysis

Build efficient PyTorch data pipelines for NLP tasks

Manage model weights for saving and loading

Setup training and inference code structures for future fine-tuning experiments

🌍 About Me
I’m Brian, an aspiring LLM engineer from Kenya, documenting my progress as I gain practical skills in NLP and large language models through structured weekly projects.

📌 Follow my progress: github.com/Okoth67


