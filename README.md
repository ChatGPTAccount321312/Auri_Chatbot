# Auri – Next-Word Predictor

**AURI** stands for **Adaptive Unigram Response Inference**.  
It is a Python project built to demonstrate the **core idea of language models**: predicting the next token in a sequence.  
Auri is intentionally **lightweight, minimal, and easy to understand**, making it a great educational tool.  
Unlike a chatbot, Auri’s scope is limited to **single-word prediction**.

---

## Features
- Predicts the **next word** based on an input sequence  
- Uses a simple **unigram-based frequency model**  
- Fully implemented in plain Python (no heavy ML frameworks required)  
- Small, clear codebase — great for beginners  
- Easy to extend with more advanced techniques (e.g., bigrams, smoothing, n-grams)  
- Ideal for learning the **fundamentals of natural language processing (NLP)**  

---

## How It Works
Auri follows a **unigram prediction strategy**:  

1. **Training phase**  
   - You provide a text dataset (e.g., a `.txt` file).  
   - Auri counts how often each word appears in the dataset.  
   - These counts are stored as unigram frequencies.  

2. **Prediction phase**  
   - When you give Auri some input text, it looks at the dataset it was trained on.  
   - Based on word frequency, it selects the **most likely candidate** for the next word.  

This demonstrates the **core principle of modern language models**:  
predicting the next token, step by step.  
While real LLMs use billions of parameters, Auri shows the same principle with **transparent, minimal code**.

---

## Requirements
- Python **3.8 or higher**  
- Recommended: a virtual environment (`venv`)  
- All dependencies are listed in `requirements.txt` (kept minimal for clarity)  

---

## Notes on Data
- Auri is **not pretrained** and ships with **no dataset**.  
- You must supply your own text data (preferably a UTF-8 plain text file).  
- The size and quality of your dataset will directly affect Auri’s predictions.  
- Example: training on *Shakespeare plays* will make predictions in old-style English, while training on *technical blogs* will bias toward modern, technical terms.  

---

## Installation

### 1. Clone the repository
```bash
git clone https://github.com/ChatGPTAccount321312/Auri_Chatbot.git
cd Auri_Chatbot
