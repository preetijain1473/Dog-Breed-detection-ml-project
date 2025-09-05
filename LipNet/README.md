# LipNet: Lipreading using Deep Learning with Conv3D and Bi-LSTM

## Overview
LipNet is a deep learning project focused on lipreading using Conv3D, MaxPool3D, Time Distributed Flatten, Bi-LSTM, and CTC Loss Function. This README provides an overview of the project, including dataset details, preprocessing steps, model architecture, training results, and instructions for getting started.

## Domain
- **Domain**: Computer Vision, Natural Language Processing (NLP), Sequence-to-Sequence Learning

## Dataset
The Grid Audio-Visual Speech Corpus dataset's subset used in this project contains:
- **Training Data**: 900 videos for training.
- **Testing Data**: 100 videos for testing.
- **Features**: Facial landmarks extracted from videos using dlib's pretrained model.

## Preprocessing
Prior to training, the following preprocessing steps are performed:
1. **Facial Landmark Extraction**: Utilizing dlib's pretrained model to extract 68 facial landmarks from each frame of the videos.
2. **Lip Region Selection**: Selecting the lip region based on the extracted facial landmarks to focus on relevant features for lipreading.

## Model Architecture
The model architecture utilized in LipNet is designed to effectively decode lip movements into sentences. Key components include:
- **Conv3D and MaxPool3D**: For spatial and temporal feature extraction from facial landmarks.
- **Time Distributed Flatten**: To maintain temporal structure while flattening the feature maps.
- **Bi-LSTM**: Bidirectional LSTM layers to capture temporal dependencies in lip movements.
- **CTC Loss Function**: Connectionist Temporal Classification loss for sequence labeling tasks.

## Training Results
- **Average Word Accuracy**: Achieved word accuracy of 91% on the testing dataset, showcasing the effectiveness of the lipreading model.

## Getting Started
1. Clone the LipNet repository from GitHub.
2. Download the Grid Audio-Visual Speech Corpus dataset's subset.
3. Preprocess the videos to extract facial landmarks and select the lip region using dlib's pretrained model.
4. Train the LipNet model using the provided notebook or code.
5. Evaluate the model on the testing dataset to assess performance.

## Acknowledgments
- Grid Audio-Visual Speech Corpus dataset: [Dataset Link](https://zenodo.org/records/3625687)
- dlib library: [dlib GitHub Repository](https://github.com/davisking/dlib)

This README provides an overview of the LipNet project, covering dataset details, preprocessing steps, model architecture, training results, and instructions for getting started with the project.
