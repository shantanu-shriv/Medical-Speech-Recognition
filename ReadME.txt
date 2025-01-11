Complete Project is split into 3 ipynb notebooks

1. main.ipynb

Contains data preprocessing, data analysis and data visualization. Followed by working of baseline Whisper base and Wev2Vec base models.

2. Whisper-FineTune.ipynb

Contains fine tuned whisper base model. This model is uploaded to Hugging Face at https://huggingface.co/shantanu007/whisper-base-shantanu

Further live demo is also present in this notebook

3. Wev2Vec-FineTune.ipynb

Contains fine tuned model for wev2vec base model.


Requirements

pandas
numpy==1.24
matplotlib
wordcloud
soundfile
librosa
openai-whisper
datasets
librosa
torchaudio
gradio
accelerate>=0.26.0
evaluate
jiwer
datasets
