🌟 Overview
Unlike traditional image captioning that focuses on object identification and scene description, this system employs multi-modal AI to infer psychological states, social dynamics, and behavioral intentions from visual information. The system combines computer vision models with advanced language models to generate rich behavioral insights.
✨ Key Features

Multi-Model Image Captioning: Utilizes both BLIP and ViT-GPT2 models for comprehensive scene understanding
Advanced Behavioral Inference: Leverages Large Language Models (Groq) for psychological and behavioral analysis
Flexible Analysis Depth: Configurable analysis levels (Basic, Detailed, Academic)
Batch Processing: Process multiple images efficiently
Google Drive Integration: Seamless cloud storage integration
Professional Documentation: Comprehensive error handling and logging

🏗️ System Architecture
Image Input → Preprocessing → Multi-Modal Captioning → Caption Fusion → 
Behavioral Analysis → Narrative Construction → Structured Output
Core Components:

BLIP Model: Salesforce/blip-image-captioning-base (~990MB)
ViT-GPT2 Model: nlpconnect/vit-gpt2-image-captioning (~1.2GB)
Groq LLM: qwen-qwq-32b for behavioral reasoning

🚀 Quick Start
Prerequisites

Python 3.7+
CUDA-compatible GPU (recommended)
12GB+ RAM (16GB recommended)
5GB free storage for model downloads

Installation

Clone the repository

bashgit clone https://github.com/PasinduDil/Behavioral-Captioning-from-Image.git
cd Behavioral-Captioning-from-Image

Install dependencies

bashpip install transformers torch torchvision pillow groq google-colab-drive matplotlib numpy requests

Set up Groq API

python# Add your Groq API key
GROQ_API_KEY = "your_groq_api_key_here"
