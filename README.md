# Complete Project: Speech Processing and Model Fine-Tuning

This project is organized into three Jupyter notebooks, each covering specific aspects of the workflow:

## Notebooks Overview

### 1. `main.ipynb`
- **Contents**:
  - Data Preprocessing
  - Data Analysis and Visualization
  - Baseline models: Whisper Base and Wav2Vec Base

---

### 2. `Whisper-FineTune.ipynb`
- **Contents**:
  - Fine-tuned Whisper Base model
  - Model uploaded to Hugging Face: [Whisper Base Shantanu](https://huggingface.co/shantanu007/whisper-base-shantanu)
  - Live demo available within the notebook

---

### 3. `Wav2Vec-FineTune.ipynb`
- **Contents**:
  - Fine-tuned Wav2Vec Base model

---

## Requirements

Ensure you have the following dependencies installed before running the notebooks:

```plaintext
pandas
numpy==1.24
matplotlib
wordcloud
soundfile
librosa
openai-whisper
datasets
torchaudio
gradio
accelerate>=0.26.0
evaluate
jiwer


