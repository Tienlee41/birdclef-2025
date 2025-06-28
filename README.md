# BirdCLEF 2025 - Bird Sound Classification

This repository contains code and notebooks for the BirdCLEF 2025 competition, focusing on bird sound classification using deep learning techniques.

## Project Structure
## Notebooks

- **EDA.ipynb**: Data exploration and visualization.
- **baseline-cnn.ipynb**: Implements a simple CNN for audio classification.
- **efficient_net/trans_ogg_to_melspec_data.ipynb**: Converts OGG audio files to Mel spectrograms for model input.
- **efficient_net/efficient_net_train.ipynb**: Advanced training pipeline using EfficientNet and various loss functions.

## Data Preprocessing

1. Use `efficient_net/trans_ogg_to_melspec_data.ipynb` to convert raw audio files into Mel spectrogram `.npy` files.
2. The generated spectrograms are used as input for model training.

## Training

- Run `efficient_net/efficient_net_train.ipynb` to train the EfficientNet model.
- Configuration options (optimizer, scheduler, loss function, etc.) are available in the notebook.

## Requirements

Install dependencies with:

```sh
pip install -r [requirements.txt]