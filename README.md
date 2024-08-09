# VGG11 Implementation on MNIST Dataset

## Overview
The goal of this project was to build a robust CNN model capable of accurately classifying handwritten digits from the MNIST dataset. The VGG11 architecture was chosen for its simplicity and effectiveness in handling image data.
Key Features:
1. Model Architecture:
- Implemented VGG11 architecture using PyTorch.
2. Training and Evaluation:
- Trained the model on the MNIST training dataset.
- Evaluated the model's accuracy on the MNIST test dataset.
3. Generalization Testing:
- Tested the model's generalization capabilities by applying random image flips and adding Gaussian noise to the test images.
4. Regularization via Data Augmentation:
- Added data augmentation techniques (random rotations, shifts, etc.) during training to reduce overfitting and improve the model's
  performance on unseen data.

## Results
The original VGG11 model achieved 98% accuracy on the MNIST test set. However, testing against flipped images and Gausiann noise significantly reduced test accuracy. After adding data augmentation as a form of regularization, it helped in reducing model variance, leading to a more robust classifier.

<img width="758" alt="image" src="https://github.com/user-attachments/assets/d26d249b-b3d1-42de-8069-ffd6298d02f6">
<img width="733" alt="image" src="https://github.com/user-attachments/assets/2ff5de41-fa28-4d7d-bf0d-d9c01a169e4c">

