# Brain Tumor Segmentation - Medical Image Analysis

**U-Net, FCN, SegNet deep learning models for pixel-level brain tumor segmentation in MRI images**

A comprehensive deep learning project for automated brain tumor segmentation using state-of-the-art convolutional neural networks. This project implements multiple semantic segmentation architectures optimized for medical image analysis with custom preprocessing pipelines.

## Features

- **Multiple Models**: U-Net, Fully Convolutional Networks (FCN), and SegNet architectures
- **Custom Preprocessing**: Advanced MRI image normalization and augmentation
- **Medical Image Ready**: Handles DICOM and medical image formats
- **Performance Metrics**: Dice Coefficient, IoU, Sensitivity, Specificity
- **Visualization Tools**: Segmentation masks overlay and comparison visualizations

## Project Overview

### Problem Statement
Manual brain tumor segmentation in MRI scans is:
- Time-consuming and subjective
- Error-prone and inconsistent
- Requires expert radiologist input

This project automates tumor boundary detection with 92%+ Dice coefficient accuracy.

## Tech Stack

- **Languages**: Python 3.9+
- **Deep Learning**: TensorFlow/Keras, PyTorch
- **Medical Imaging**: SimpleITK, Nibabel, OpenCV
- **Data Processing**: Numpy, Scipy, Pandas
- **Visualization**: Matplotlib, Seaborn

## Getting Started

### Prerequisites
```bash
pip install tensorflow keras torch torchvision numpy opencv-python nibabel simpleitk
```

### Dataset
This project is compatible with:
- BRATS (Brain Tumor Segmentation) dataset
- Custom MRI DICOM files
- NIfTI format medical images

## Models Implemented

### U-Net
Encoder-decoder architecture with skip connections for precise segmentation.
- Symmetric architecture
- Skip connections preserve spatial information
- Ideal for medical image segmentation

### FCN (Fully Convolutional Networks)
End-to-end pixel-wise classification.
- No fully connected layers
- Efficient for large images
- Fast inference time

### SegNet
Light-weight encoder-decoder with pooling indices.
- Memory efficient
- Preserves spatial resolution
- Good for medical imaging

## Performance

| Model | Dice Coefficient | IoU | Sensitivity |
|-------|------------------|-----|-------------|
| U-Net | 0.92 | 0.85 | 0.94 |
| FCN | 0.89 | 0.82 | 0.91 |
| SegNet | 0.90 | 0.83 | 0.92 |

## Author

**Abd Al-Rahman Mohamed**
- AI Engineer | Deep Learning Specialist
- Email: abdalrahman.mohamed.nafie@gmail.com
- LinkedIn: [abdalrhman-mohamed-72ab63237](https://linkedin.com/in/abdalrhman-mohamed-72ab63237)

---

If this project helped you, please star it!
