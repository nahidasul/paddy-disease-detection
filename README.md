# A Comparative Evaluation of Lightweight and Conventional Deep Learning Models for Offline Bangladeshi Rice Leaf Disease Classification

This project evaluates and compares two deep learning models for offline classification of rice leaf diseases using a Bangladeshi rice leaf disease dataset.

## Objective
To assess the trade-off between lightweight and conventional deep learning architectures in terms of classification performance, model size, and inference efficiency for rice disease detection.

## Dataset
- Source: Mendeley Data
- Link: https://data.mendeley.com/datasets/vwv3nry3wr/1
- Dataset: Offline Bangladeshi rice leaf disease images
- Input size: 224 x 224

## Models
1. MobileNetV2
   - Pretrained on ImageNet
   - Input size: 224 x 224
   - Lightweight architecture optimized for mobile and resource-constrained deployment

2. EfficientNetB0
   - Pretrained on ImageNet
   - Input size: 224 x 224
   - Efficient conventional convolutional model with strong accuracy-performance balance

## Evaluation Metrics
The models are assessed using standard classification metrics, including:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix
- Classification report

## Model Comparison
In addition to predictive performance, the project also compares:
- Model size (MB)
- Inference time per image
- Computational efficiency
- Practical suitability for offline deployment

## Project Workflow
- Load and preprocess the dataset
- Split data into train/validation/test sets
- Fine-tune MobileNetV2 and EfficientNetB0
- Evaluate on standard metrics
- Compare results based on accuracy and efficiency

## Requirements
- Python 3.x
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- scikit-learn

## Notes
The study focuses on identifying which model offers the best balance between classification accuracy and deployment efficiency for Bangladeshi rice leaf disease recognition in offline environments.
