# Meme Shield 🛡️

## Overview
Meme Shield is a multimodal deep learning project designed to classify memes as toxic or non-toxic by analyzing both image content and embedded text.

## Models

1. **Image Model** — Uses EfficientNetB0 for image-based classification.
2. **Text Model** — Uses DistilBERT for text toxicity classification.
3. **Merge Model** — Combines image predictions with OCR-extracted text predictions to produce a final classification.

## Project Structure

- `image_model.ipynb` — Image classification model
- `text_model.ipynb` — Text toxicity classification model
- `merge_model.ipynb` — Multimodal prediction pipeline

## Technologies Used

- Python
- TensorFlow / Keras
- PyTorch
- Hugging Face Transformers
- EasyOCR / Tesseract OCR
- Google Colab

## How to Run

1. Open the required notebook in Google Colab.
2. Install the dependencies specified in the notebook.
3. Configure the dataset and trained-model paths.
4. Run the cells in order.

**Note:** Dataset files and trained model weights may need to be downloaded or configured separately.

## Project Goal

To help identify toxic content in memes by analyzing both their visual features and embedded text.# Meme--shield
Multimodal toxic meme detection using text and image deep learning models.
