# ParaBangla: Bangla Paraphrase Detection using BanglaBERT + LSTM

This repository contains the implementation of a **paraphrase detection system** for Bangla text. The system combines **BanglaBERT** and **LSTM** to classify whether two Bangla sentences are paraphrases of each other. The model uses the **BnPC paraphrased dataset** and achieves an accuracy of **84.56%** on the test dataset.

## Project Overview

Paraphrase detection is the task of identifying if two sentences express the same meaning in different ways. This project applies a combination of pre-trained **BanglaBERT** for feature extraction and **LSTM** for sequence modeling to detect paraphrases in Bangla text.

### Key Components:
- **BanglaBERT**: A pre-trained transformer model for the Bangla language that helps in understanding the semantics of the text.
- **LSTM (Long Short-Term Memory)**: A type of recurrent neural network used to model sequential dependencies and capture long-term dependencies in the text.
- **BnPC Dataset**: A dataset of paraphrased Bangla sentences that is used to train and evaluate the model.

## Features
- **Paraphrase Detection**: Classifies pairs of sentences as paraphrases (1) or non-paraphrases (0).
- **Bangla Language Support**: Designed specifically for Bangla text, but the architecture can be adapted to other languages.
- **High Accuracy**: The model achieved an accuracy of 84.56% on the test dataset.

