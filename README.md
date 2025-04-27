# Deepfake and Fake Review Detection

This project provides a simple web interface to detect deepfake images and fake reviews using machine learning models. It integrates the **VGG16** model for deepfake detection and the **DistilBERT** model fine-tuned for sentiment analysis to detect fake reviews.

## Features

- **Deepfake Image Detection:** Uses the VGG16 pre-trained model to detect if an image is real or fake.
- **Fake Review Detection:** Uses a fine-tuned DistilBERT model to classify reviews as "Real" or "Fake."

## Requirements

- Python 3.x
- `tensorflow`
- `opencv-python`
- `transformers`
- `huggingface_hub`
- `streamlit` (for the web interface)
