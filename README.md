# Fine-Tuning Wav2Vec2 for Emotion Recognition: Pruning vs Knowledge Distillation

## Overview

This repository focuses on fine-tuning the [Wav2Vec2 model](https://huggingface.co/models) for the downstream task of **emotion recognition** using audio data. The project explores two optimization techniques:
1. **Pruning**: Reducing model size by removing less significant weights or layers.
2. **Knowledge Distillation (KD)**: Training a smaller "student" model to mimic a larger "teacher" model.

The results of these techniques will be compared in terms of:
- Model performance (accuracy, F1-score, etc.)
- Computational efficiency (inference time, model size, etc.)

## Features
- Preprocessing and loading datasets for emotion recognition.
- Fine-tuning the Wav2Vec2 model on labeled emotion datasets.
- Implementing pruning to reduce model complexity.
- Applying knowledge distillation to create efficient student models.
- Comparing the performance and efficiency of the optimized models.

## Datasets
We utilize publicly available datasets for emotion recognition:
- [CREMA-D](https://www.kaggle.com/datasets/ejlok1/cremad)

## Model Architecture
The project fine-tunes the [Wav2Vec2-base](https://huggingface.co/facebook/wav2vec2-base) model. Both the base and pruned/distilled versions are evaluated to study the trade-offs between performance and efficiency.



