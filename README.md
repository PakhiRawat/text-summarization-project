# Abstractive Text Summarization Using BART

This project implements an abstractive text summarization system using **Transformer-based deep learning**, specifically the **BART (Bidirectional and Auto-Regressive Transformers)** model. The system takes long input text and generates a concise, meaningful summary. It also includes a **Gradio-based web interface** that allows users to input any text and receive a summarized output instantly.

---

## 1. Project Overview

- Uses the **BART-large CNN** model for abstractive summarization  
- Generates new, human-like sentences instead of copying text  
- Light fine-tuning is performed on a small subset of the BillSum dataset  
- Provides an interactive **Gradio UI** for easy demonstration  

---

### **Key Advantages**
- Handle long text effectively  
- Enable parallel processing for fast training  
- Provide strong contextual understanding  
- Achieve state-of-the-art performance in NLP tasks  

---

## 2. Model Used: BART

- **BART = Bidirectional and Auto-Regressive Transformers**  
- Uses an **encoder–decoder** architecture  
- Encoder understands the input text  
- Decoder generates the summary  
- Pretrained on massive text corpora  
- Excellent for summarization, translation, rewriting  

---

## 4. Dataset: BillSum

The **BillSum dataset** contains U.S. legislative bills and their human-written summaries.

### **Dataset Includes:**
- **text** → long legislative document  
- **summary** → concise human-generated summary  
- A small subset (200 samples) was used for light fine-tuning  

---

## 5. Project Workflow

1. **Install required libraries** (Transformers, Datasets, Gradio)  
2. **Load the BillSum dataset**  
3. **Inspect sample documents and summaries**  
4. **Load the pretrained BART model**  
5. **Perform light fine-tuning** on a small
