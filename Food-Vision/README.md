# Food Vision: Deep Learning Food Classification Project

## Overview
Food Vision is a deep learning project aimed at classifying 101 classes of food using the Food101 dataset. Transfer learning techniques have been employed to create a robust food classification model. This README provides an overview of the project, its structure, and the rationale behind using EfficientNetB0 as the backbone architecture. Additionally, it discusses the integration of Weights and Biases for tracking project progress.

## Domain
- **Domain**: Computer Vision, Transfer Learning

## EfficientNetB0
EfficientNetB0 is chosen as the backbone architecture for several reasons:
- **Efficiency**: EfficientNet models are designed to achieve better accuracy while being computationally efficient.
- **Scalability**: The model scales uniformly in depth, width, and resolution to adapt to different computational resources and constraints.
- **Transfer Learning**: EfficientNetB0 has been pre-trained on ImageNet, making it suitable for transfer learning tasks like food classification.
- **Performance**: It has demonstrated state-of-the-art performance on various image classification benchmarks.

## Weights and Biases Integration
Weights and Biases (wandb) is integrated into the project for experiment tracking and visualization. It offers several benefits:
- **Experiment Monitoring**: Track and visualize model metrics, losses, and performance over time.
- **Hyperparameter Tuning**: Easily compare different hyperparameter settings and configurations.

## Results
The best model achieved an impressive accuracy of 75.24% on the Food101 dataset, which consists of 101 classes of food. This accuracy showcases the effectiveness of the deep learning approach, particularly utilizing transfer learning with EfficientNetB0 as the backbone architecture. The model's ability to accurately classify various food items demonstrates its robustness and potential for real-world applications in food recognition and classification tasks.

To reproduce the experiments and track progress using Weights and Biases, make sure to set up a wandb account and provide the necessary API key for integration.

## Getting Started
1. Open the notebook in Google Colab.
2. Copy the notebook and feel free to use it for your experiments.

## Acknowledgments
- Food101 dataset: [Food101 - An Image Dataset for Food Recognition](https://data.vision.ee.ethz.ch/cvl/datasets_extra/food-101/)
- EfficientNet paper: [EfficientNet: Rethinking Model Scaling for Convolutional Neural Networks](https://arxiv.org/abs/1905.11946)
- Weights and Biases documentation: [wandb Documentation](https://docs.wandb.ai/)
