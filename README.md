# Behavioral Captioning from Images

[![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)](https://python.org)
[![PyTorch](https://img.shields.io/badge/PyTorch-Latest-red.svg)](https://pytorch.org)
[![Transformers](https://img.shields.io/badge/🤗%20Transformers-Latest-yellow.svg)](https://huggingface.co/transformers)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

An advanced AI system that transforms visual scenes into nuanced behavioral narratives using multi-modal deep learning and large language models.

## 🌟 Overview

Unlike traditional image captioning that focuses on object identification and scene description, this system employs multi-modal AI to infer psychological states, social dynamics, and behavioral intentions from visual information. The system combines computer vision models with advanced language models to generate rich behavioral insights.

## ✨ Key Features

- **Multi-Model Image Captioning**: Utilizes both BLIP and ViT-GPT2 models for comprehensive scene understanding
- **Advanced Behavioral Inference**: Leverages Large Language Models (Groq) for psychological and behavioral analysis
- **Flexible Analysis Depth**: Configurable analysis levels (Basic, Detailed, Academic)
- **Batch Processing**: Process multiple images efficiently
- **Google Drive Integration**: Seamless cloud storage integration
- **Professional Documentation**: Comprehensive error handling and logging

## 🏗️ System Architecture

```
Image Input → Preprocessing → Multi-Modal Captioning → Caption Fusion → 
Behavioral Analysis → Narrative Construction → Structured Output
```

### Core Components:
- **BLIP Model**: Salesforce/blip-image-captioning-base (~990MB)
- **ViT-GPT2 Model**: nlpconnect/vit-gpt2-image-captioning (~1.2GB)
- **Groq LLM**: qwen-qwq-32b for behavioral reasoning

## 🚀 Quick Start

### Prerequisites

- Python 3.7+
- CUDA-compatible GPU (recommended)
- 12GB+ RAM (16GB recommended)
- 5GB free storage for model downloads

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/PasinduDil/Behavioral-Captioning-from-Image.git
cd Behavioral-Captioning-from-Image
```

2. **Install dependencies**
```bash
pip install transformers torch torchvision pillow groq google-colab-drive matplotlib numpy requests
```

3. **Set up Groq API**
```python
# Add your Groq API key
GROQ_API_KEY = "your_groq_api_key_here"
```

## 🎯 Example Results

### Input: Classroom Scene
**Generated Analysis:**
> "The central behavior depicted is the students actively participating in the lesson by raising their hands, likely in response to a question or prompt from the teacher, indicating engagement and eagerness to contribute."

### Input: Bus Stop Scene
**Generated Analysis:**
> "The main thing they're doing is sitting on the bench, but the reason for being there is to wait for the bus. So maybe 'Waiting for public transportation' is the primary activity."

### Input: Presentation Scene
**Generated Analysis:**
> "The main behavior depicted is a collaborative or educational task, such as a presentation or discussion. One person may be operating or explaining content via a projector, while another individual contributes to or observes the presentation."

## 🔧 Configuration

### Model Selection
```python
# Primary model (recommended)
MODEL = "qwen-qwq-32b"

# Alternative model
MODEL = "llama2-70b-4096"
```

## 🙏 Acknowledgments

- Salesforce for the BLIP model
- Hugging Face for the transformers library
- Groq for LLM API services
- The open-source AI community

## 📞 Contact

**Pasindu Dilshan**
- GitHub: [@PasinduDil](https://github.com/PasinduDil)
- Project Link: [https://github.com/PasinduDil/Behavioral-Captioning-from-Image](https://github.com/PasinduDil/Behavioral-Captioning-from-Image)
