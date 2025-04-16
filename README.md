# NYCU Computer Vision 2025 Spring — HW2

**StudentID**: 313554802
**Name**: Sophie Fu

## Introduction

This project addresses a digit recognition task using the Faster R-CNN object detection framework. It is divided into two subtasks:

- **Task 1**: Detect all digits in an image and classify them individually by predicting bounding boxes and class labels.
- **Task 2**: Reconstruct the full number by ordering the detected digits from left to right.

All models were trained and evaluated using PyTorch on Google Colab. Custom preprocessing and visualization tools were implemented for COCO-style annotations.

## How to install

Run this notebook in Google Colab.
Before running, mount your Google Drive and ensure your dataset is under: /content/drive/MyDrive

Otherwise you should change the dataset_root path


## Requirements

- Python 3.8+
- PyTorch ≥ 1.10
- Torchvision ≥ 0.11
- pycocotools
- PIL (Pillow)
- NumPy
- Matplotlib
- tqdm

### Installation (recommandé sur Google Colab)
```bash
pip install torch torchvision pycocotools matplotlib tqdm Pillow
```
## Performance snapshot
![Capture d'écran 2025-04-16 201739](https://github.com/user-attachments/assets/825103a9-6ba7-4a5c-91a6-f8c4c3d9c10b)
