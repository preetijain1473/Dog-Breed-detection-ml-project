# Dog Vision: Deep Learning Dog Breed Classification Project

## Overview
Dog Vision is a deep learning project focused on classifying dog breeds using the Kaggle Dog Breed Identification Competition dataset. This README provides an overview of the project, including dataset details, model architecture, training results, and acknowledgments.

## Domain
- **Domain**: Computer Vision, Transfer Learning

## Dataset
The Kaggle Dog Breed Identification Competition dataset contains:
- **Training Data**: 10,200 labeled images, each mapped to one of 120 dog breeds.
- **Testing Data**: 10,400 images without provided labels.
- **CSV File**: `labels.csv` maps image file names to corresponding dog breeds.

## Model Architecture
EfficientNetB0 is employed as the backbone architecture for feature extraction due to:
- **Computational Efficiency**: EfficientNet models offer better accuracy while being computationally inexpensive, suitable for projects with limited resources.
- **Transfer Learning**: Pre-trained on ImageNet, EfficientNetB0 facilitates effective transfer learning for dog breed classification tasks.
- **Performance**: Despite computational efficiency, EfficientNetB0 delivers impressive performance on image classification benchmarks.

## Training Results
- **Training Accuracy**: Achieved 89% accuracy on the training dataset, showcasing effective learning of dog breed features.
- **Test Dataset**: Evaluation on the test dataset wasn't possible due to unavailability of labels.

## Getting Started
1. Download the Kaggle Dog Breed Identification Competition dataset.
2. Ensure presence of `labels.csv` and image data.
3. Utilize provided notebook or code to train EfficientNetB0 for dog breed classification.

## Acknowledgments
- Kaggle Dog Breed Identification Competition: [Kaggle Competition](https://www.kaggle.com/c/dog-breed-identification)
- EfficientNet paper: [EfficientNet: Rethinking Model Scaling for Convolutional Neural Networks](https://arxiv.org/abs/1905.11946)

This README provides an overview of the Dog Vision project, covering dataset details, model architecture, training results, and instructions for getting started with the project.
