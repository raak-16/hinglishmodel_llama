# Hinglish Voice-AI Fine-Tuning Project

## 📖 Project Overview
This project fine-tunes the Llama 3 open-source LLM to handle code-switched Hinglish dialogue for Voice-AI applications. Instead of using OpenAI's API as originally suggested, we've implemented an open-source alternative using Meta's Llama 3 model with Unsloth for efficient fine-tuning.

## 🛠️ Technical Approach

### Why Llama 3 instead of OpenAI?
- **No credit card required** - Completely open-source solution
- **Data privacy** - All processing happens locally/in your infrastructure
- **Customizability** - Full control over model architecture and training process
- **Cost-effective** - No per-token charges for inference

### Dataset Preparation (`dataset.jsonl`)
Collected 20 Hinglish conversation examples focusing on:
- Everyday casual conversations
- Code-switching patterns (Hindi + English)
- Common Voice-AI interaction scenarios

Example format:
```json
{"prompt":"User: Kaise ho?\nAssistant:","completion":"Main theek hoon, thanks for asking!"}
{"prompt":"User: Sunday ko kya plan hai?\nAssistant:","completion":"Shayad movie dekhne jaun."}



hf link -- https://huggingface.co/raak-16/hinglish_model-ai
