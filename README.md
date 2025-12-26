# Universal Language Speech ↔ Text Translator (STT + Translate + TTS)

A multilingual speech and text translation pipeline supporting:
- Speech → Text using Wav2Vec2
- Text → Text translation using M2M100
- Text → Speech using SpeechT5 + HiFi-GAN
- Interactive Gradio UI

This repository is built from the implementation in `notebooks/Speech_project.ipynb`.

## Models Used
- Wav2Vec2 (Large & Base) – Speech-to-Text
- M2M100 – Multilingual Translation
- SpeechT5 + HiFi-GAN – Text-to-Speech
- gTTS + SpeechRecognition (baseline)

## Tech Stack
Python, PyTorch, torchaudio, Hugging Face Transformers, Gradio

## Installation
```bash
pip install -r requirements.txt
```

## License
MIT License
