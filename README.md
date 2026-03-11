## Run in Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]
(https://colab.research.google.com/github/Ashwiniii770/differentially-private-deep-learning/blob/main/Differentially_Private_Deep_Deep_Learning.ipynb)
# Differentially Private Deep Learning

This project demonstrates how to train a deep learning model while preserving user data privacy using Differential Privacy.

## Technologies Used
- PyTorch
- Opacus
- MNIST Dataset
- Matplotlib

## Features
- Training neural networks with differential privacy
- Privacy budget (ε) calculation
- Model accuracy evaluation
- Training loss visualization
- Privacy vs accuracy tradeoff analysis

## Dataset
MNIST handwritten digit dataset.

## Results
| Model | Accuracy | Privacy |
|------|---------|---------|
| Normal Model | ~96% | None |
| Private Model | ~70-85% | ε ≈ 0.2 |

## Installation

```bash
pip install torch torchvision opacus matplotlib

## Results

### Model Prediction
Example of the model predicting a handwritten digit.

![Prediction](images/prediction_example.png)

### Training Loss Curve
Training loss over iterations during model training.

![Training Loss](images/training_loss.png)

### Training Progress
Model training output showing decreasing loss over epochs.

![Training Output](images/training_epochs_output.png)

## Model Evaluation

### Model Accuracy
The model achieved approximately **70.6% accuracy** on the MNIST dataset when trained with Differential Privacy.

![Model Accuracy](images/model_accuracy.png)

## Key Results

| Metric | Value |
|------|------|
| Dataset | MNIST |
| Model Accuracy | 70.6% |
| Privacy Budget (ε) | ~0.22 |
| Framework | PyTorch + Opacus |
