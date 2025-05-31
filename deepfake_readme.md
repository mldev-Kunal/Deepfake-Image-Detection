# Deepfake Image Detection

A lightweight deep learning model utilizing Channel & Spatial Attention mechanisms for binary classification of deepfake images as Real or Fake.

## Overview

This project implements an efficient deepfake detection system that leverages attention mechanisms to improve classification accuracy while maintaining computational efficiency. The model has been trained and evaluated on multiple datasets to ensure robustness and generalizability.

## Datasets

- **OpenForensics**: Primary dataset used for training and testing
- **DFDC (Image)**: Secondary dataset used for assessing model generalizability

## Model Architecture

The model incorporates:
- **Channel Attention**: Focuses on important feature channels
- **Spatial Attention**: Emphasizes relevant spatial regions
- **Lightweight Design**: Optimized for efficiency without compromising accuracy

## Files Overview

### Documentation & Visualizations
- `Sample.pdf` - Training dataset visualization
- `DNetwork.pdf` - Complete network architecture diagram
- `CA.pdf` - Channel attention mechanism diagram
- `Sa.pdf` - Spatial attention mechanism diagram

### Training Results
- `train.png` - Training and validation accuracy/loss curves per epoch

### Performance Evaluation

#### OpenForensics Dataset
- `Conf.png` - Confusion matrix
- `roc.png` - ROC curve

#### DFDC Dataset (Image only)
- `Dconf.png` - Confusion matrix
- `Droc.png` - ROC curve

## Key Features

- ✅ Lightweight architecture suitable for real-time applications
- ✅ Dual attention mechanism (Channel + Spatial)
- ✅ Cross-dataset validation for generalizability
- ✅ Comprehensive performance evaluation with multiple metrics

## Results Summary

The model demonstrates strong performance on both datasets:
- High accuracy on the OpenForensics dataset
- Good generalization capability when tested on DFDC dataset
- Effective attention mechanisms as shown in the visualization diagrams

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---
