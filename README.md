# Auri – Next-Word Predictor

**AURI** stands for **Adaptive Unigram Response Inference**.  
It is a Python project that predicts the next word in a sequence of text.  
Auri is lightweight, educational, and designed to demonstrate the fundamentals of next-token generation.  
It is not a chatbot — Auri focuses purely on single-word prediction.

---

## Features
- Predicts the next word given an input sequence
- Implements a simple unigram-based model
- Lightweight Python implementation
- Easy to read and extend
- Useful for learning about the basics of language modelling

---

## How It Works
Auri uses a **unigram prediction approach**.  
Given some input text, it calculates the most likely next word from its training data or rules.  

This simple method demonstrates the **core principle behind larger language models**:  
predicting the next token, one step at a time.  

---

## Requirements
- Python 3.8 or higher  
- Recommended: a virtual environment (`venv`)  
- Any additional dependencies will be listed in `requirements.txt`

---

## Note
Auri is **not pretrained** and does not include a dataset. 
You must provide your own training data (for example, a UTF-8 text file) and train the model before using it.


---

## Installation

### 1. Clone the repository
```bash
git clone https://github.com/ChatGPTAccount321312/Auri_Chatbot.git
cd Auri_Chatbot
