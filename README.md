# 🕯️ Poe Text Generator
## Fine-Tuning GPT-2 on Edgar Allan Poe’s Public-Domain Works

*Where neural networks meet candlelight.*

This project fine-tunes a **GPT-2** language model on the public-domain writings of Edgar Allan Poe to generate new text in a Poe-inspired literary style.  
It blends classical literature with modern Transformer-based deep learning.

---

## 📖 About the Project

This repository contains a complete NLP pipeline implemented in a Jupyter notebook.

The workflow includes:

- 📥 Downloading Poe’s texts from Project Gutenberg  
- 🧹 Cleaning and merging raw literary data  
- 🔠 Tokenization and sequence chunking  
- 🧠 Fine-tuning GPT-2 using HuggingFace Transformers  
- 🌫️ Generating new Poe-style passages  

This project serves both as:

- A practical Transformer fine-tuning exercise  
- A stylistic experiment in computational literature  

---

## 🧠 Model Details

- **Base Model:** `gpt2`  
- **Framework:** HuggingFace Transformers + PyTorch  
- **Training Type:** Full fine-tuning  
- **Environment:** Google Colab (GPU recommended)

### Why GPT-2?

- Lightweight enough for experimentation  
- Strong baseline for stylistic modeling  
- Fast training cycle  

---

## 🔁 Pipeline Overview

1. Download corpus  
2. Clean and preprocess text  
3. Tokenize and chunk sequences  
4. Fine-tune GPT-2  
5. Generate new text samples  

---

## 🚀 Running the Project

### 1️⃣ Clone the repository

```bash
git clone https://github.com/rshahri/poe-text-generator.git
cd poe-text-generator
```
### 2️⃣ Install dependencies

```bash
git clone https://github.com/rshahri/poe-text-generator.git
cd poe-text-generator
```
### 3️⃣ Open the notebook

```bash
notebooks/poe_text_generator.ipynb
```

Run all cells sequentially from top to bottom.

**⚡ GPU strongly recommended for training.**

---

## 🌒 Text Generation Controls

After training, the model generates new Poe-style passages.

Generation can be controlled using:

- temperature — controls randomness

- top_p — nucleus (probability mass) sampling

- max_length — length of generated text

Small changes to these parameters significantly affect tone, coherence, and creativity.

---

## 📚 Data Source

Texts are downloaded at runtime from Project Gutenberg public-domain editions of Edgar Allan Poe’s works.

No raw Gutenberg files are stored in this repository.

---


## ⚠️ Limitations

- Repetition may occur

- Long-range narrative coherence is limited

- Stylistic similarity does not imply semantic accuracy

- The model captures statistical patterns rather than authorial intent


---


## 🔬 Educational Value

This project demonstrates:

- Transformer fine-tuning

- Literary style modeling

- Text preprocessing for language models

- Decoding strategy experimentation

It bridges classical literature and modern AI systems.

---

## 📜 License

This project is licensed under the MIT License.
You are free to use, modify, and distribute this software with proper attribution.
