# Masked-Face-Classification-and-Recognition

## Overview
This project addresses the growing need for Artificial Intelligence algorithms to tackle issues related to mask usage in the context of the COVID-19 pandemic. Focusing on both classification and recognition tasks, the team developed five models using Convolutional Neural Networks (CNNs) and Transfer Learning. The models aim to classify individuals based on mask presence, gender, and recognize masked faces.

## Motivation
With the increasing importance of wearing masks for virus prevention, there's a demand for AI solutions to ensure compliance with safety protocols. This project contributes by developing efficient algorithms for mask classification and recognition, offering insights into adherence to sanitary guidelines.

## Methodology
The project employs two main architectures: one utilizing CNNs developed from scratch, and another leveraging MobileNetV2 for Transfer Learning. Different cases are addressed, including simple mask detection, masked-face gender classification, and face recognition. Data augmentation techniques are applied to address data insufficiency, and three datasets are created for specific scenarios.


## Implementation and Results
**Datasets**: Created three datasets, combining public datasets and self-collected data.
**Data Augmentation**: Utilized various techniques such as flipping, cropping, zooming, shifting, and rotation.
**Training**: TensorFlow used for training, with specific settings for each model.
**Metrics**: Accuracy for all models, AUC for transfer learning-based models.
**Results**: Achieved high accuracy, particularly in the simple mask detection case, with noticeable impact from transfer learning.

