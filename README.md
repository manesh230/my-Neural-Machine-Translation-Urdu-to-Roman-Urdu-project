# my-Neural-Machine-Translation-Urdu-to-Roman-Urdu-project
Sequence-to-sequence BiLSTM model for transliterating Urdu Ghazals into Roman Urdu using the urdu_ghazals_rekhta dataset.
# Urdu → Roman Urdu Neural Machine Translation (BiLSTM)

This repository contains code for building a sequence-to-sequence BiLSTM model that transliterates Urdu Ghazals into Roman Urdu using the [urdu_ghazals_rekhta](https://github.com/amir9ume/urdu_ghazals_rekhta) dataset.

## Objectives
- Preprocess Urdu Ghazal text
- Build a BiLSTM encoder + LSTM decoder model in PyTorch
- Train, evaluate, and experiment with different hyperparameters
- Deploy the final model with a Streamlit interface

## Dataset
We use the *urdu_ghazals_rekhta* dataset. See `/data` for scripts to download and preprocess.

## Project Structure
- `src/data` – data loading & preprocessing scripts
- `src/model` – BiLSTM encoder-decoder model
- `src/training` – training scripts
- `src/evaluation` – evaluation metrics (BLEU, Perplexity, CER)
- `streamlit_app` – deployment app
- `notebooks` – exploratory notebooks
- `experiments` – YAML configs for hyperparameter experiments

## Installation
```bash
git clone https://github.com/<your-username>/Urdu-RomanUrdu-NMT-BiLSTM.git
cd Urdu-RomanUrdu-NMT-BiLSTM
pip install -r requirements.txt
