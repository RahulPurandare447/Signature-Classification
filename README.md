# Handwritten Signature Verification

This project involves the development of a machine learning model to verify handwritten signatures. The dataset consists of genuine and forged signature images, which are used to train a classification model to distinguish between authentic and fake signatures.

## Project Overview

In this project, we will:
- Download and preprocess the dataset of handwritten signatures.
- Implement image preprocessing techniques (grayscale, resizing, and normalization).
- Build a machine learning pipeline to classify signatures as **genuine** or **forged**.
- Visualize some sample images from the dataset.

### Dataset

The dataset used for this project is from the Kaggle dataset **"Handwritten Signature Verification"** by [tienen](https://www.kaggle.com/tienen/handwritten-signature-verification). It contains genuine and forged signatures.

### Steps

1. **Dataset Download and Extraction**:
   The dataset is downloaded from Kaggle and extracted into the `signature_dataset` directory.

2. **Data Preprocessing**:
   - Signature images are loaded and resized to 128x128 pixels.
   - Images are converted to grayscale for simpler processing.
   - Pixel values are normalized to the range [0, 1].

3. **Model Training**:
   - The data is split into training and test sets using `train_test_split`.
   - Machine learning models (e.g., Convolutional Neural Networks) can be trained on this dataset to classify signatures.

4. **Visualization**:
   - Random samples from the dataset are displayed to visualize the images.

### File Structure

