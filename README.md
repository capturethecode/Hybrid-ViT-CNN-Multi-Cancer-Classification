<<<<<<< HEAD

# Hybrid Vision Transformer-CNN Architecture for Multi-Cancer Classification

## Overview
This project implements a hybrid deep learning architecture combining Vision Transformer (ViT) and Convolutional Neural Networks (CNN) for multi-cancer classification.

## Key Features
- Hybrid ViT-CNN architecture.
- Global and local feature representation.
- Multi-scale feature extraction using 3×3, 5×5, and 7×7 parallel convolutions.
- Classification across 9 cancer classes.
- Real-time inference through a local application.

## Dataset
- 72,000+ medical images.
- 9 classification classes.
- Dataset source and access instructions: [Add dataset details]

## Model Performance
- Test Accuracy: 96.21%
- Optimizer: AdamW
- Regularization: Label Smoothing

## Tech Stack
- Python
- PyTorch
- Vision Transformer
- CNN
- NumPy
- Matplotlib

## Project Structure
See the repository folders for model implementation, training, evaluation, and inference.

## Installation
```bash
git clone https://github.com/YOUR_USERNAME/Hybrid-ViT-CNN-Multi-Cancer-Classification.git
cd Hybrid-ViT-CNN-Multi-Cancer-Classification
pip install -r requirements.txt
```

## Run the Project
```bash
python src/train.py
```

## Results
Add your accuracy graph, confusion matrix, and sample predictions here.

## Author
Abhishek Kumar

=======
# Multi Cancer diagnosis using Histopathological images
This project presents a hybrid CNN + Vision Transformer model for multi-cancer histopathological image classification.

## Features
- CNN + Vision Transformer
- Histopathological Image Analysis
- Multi-class Cancer Diagnosis
- Streamlit Web Application

## Accuracy
- CNN Accuracy: 90.56%
- CNN + Vision Transformer Accuracy: 96.21%

## Run Application

streamlit run app/app.py
>>>>>>> 0e6eb16 (Initial commit: Hybrid ViT-CNN Multi-Cancer Classification)
