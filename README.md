# 🎭 Shakespearean Chatbot

Transform modern English conversations into eloquent Shakespearean dialogue with this fine-tuned chatbot! Leveraging advanced natural language processing (NLP) techniques, this project demonstrates the power of AI models like GPT-2 and T5 for generating meaningful and stylistically transformed responses.

---

## 📚 Project Overview

This chatbot:
1. **Predicts the next possible response** in a conversation using a pretrained GPT-2 model.
2. **Converts the predicted response** into Shakespearean English using a fine-tuned T5 model.

### 🧠 Key Features:
- **Next Sentence Prediction:** The GPT-2 model generates contextually appropriate replies.
- **Style Transfer:** Fine-tuned T5 translates modern English into Shakespearean prose.
- **Integrated Training Pipeline:** Custom training and preprocessing pipelines for data alignment and tokenization.

---

## ⚙️ Technology Stack

- **Google Colab:** For training and testing the models.
- **Python:** The primary programming language.
- **Hugging Face Transformers:** For GPT-2 and T5 model integration.
- **PyTorch:** Deep learning framework used for training the models.
- **Datasets Library:** Simplifies dataset preparation and preprocessing.

---

## 🛠️ How It Works

1. **Data Preparation:**  
   - Used aligned datasets from Shakespeare's *Romeo and Juliet* for training.
   - Mapped modern English sentences to their Shakespearean counterparts.

2. **Training Pipeline:**  
   - Fine-tuned a `T5-small` model for English-to-Shakespearean translation.
   - Used a GPT-2 model for next-sentence prediction.

3. **Chatbot Flow:**  
   - The user provides input in modern English.
   - GPT-2 predicts the next logical response in English.
   - The T5 model translates the response into Shakespearean English.

---

## 🚀 Installation

### Prerequisites:
- Python 3.8 or above.
- Required libraries: `transformers`, `datasets`, `torch`, `sentencepiece`.
