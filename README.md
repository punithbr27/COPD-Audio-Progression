# COPD-Audio-Progression


# COPD Audio Progression Prediction

This project predicts COPD stage progression using respiratory audio recordings. It uses log-mel spectrograms and CNN-based classification models for transitions like COPD0 → COPD1, COPD3 → COPD4, etc.

## 🚀 Features
- MFCC and log-mel spectrogram feature extraction
- Deep learning models (CNN)
- Data augmentation for limited samples
- Patient-level prediction averaging
- Visualization and explainability (Grad-CAM)

## 📂 Structure
- `src/`: Python scripts
- `notebooks/`: Exploratory notebooks
- `models/`: Saved trained models (ignored in Git)
- `data/`: Raw audio and labels (not pushed to GitHub)

## 🛠️ Installation

```bash
pip install -r requirements.txt
