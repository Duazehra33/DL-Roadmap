# Deep Learning – Week 02
## Phase 2: Convolutional Neural Networks (CNNs)

### Overview

This repository contains the theoretical and practical learning materials for Week 2 of Deep Learning, focusing on Convolutional Neural Networks (CNNs) and their applications in image classification.

The materials cover CNN architecture, image processing, feature extraction, and deep learning techniques for building and training image classification models.

The repository includes a theoretical PDF, three practical Jupyter Notebooks, and an external dataset resource for custom image classification.

## Repository Contents

### 1. `week 2 convolutional neural networks.pdf`
**Theory and Conceptual Understanding**

This PDF covers the theoretical foundations of Convolutional Neural Networks, including:

- Introduction to Convolutional Neural Networks.
- Image representation and processing.
- Convolution operations and filters.
- Feature Maps and Feature Extraction.
- Padding and Stride.
- Pooling Operations.
- Dropout and Batch Normalization.
- CNN Architectures:
  - LeNet
  - VGG
  - ResNet (Introduction)
- CNN applications in image classification.

### 2. `CIFAR10.ipynb`
**CIFAR-10 Image Classification**

This notebook demonstrates CNN-based image classification using the CIFAR-10 dataset.

Key areas covered:

- Loading and preprocessing image data.
- Understanding image dimensions and color channels.
- Building a CNN architecture from scratch.
- Applying convolution and pooling layers.
- Training and validating the classification model.
- Applying regularization techniques.
- Evaluating classification performance.
- Visualizing predictions and model results.

### 3. `Fashin_MNIST.ipynb`
**Fashion-MNIST Image Classification**

This notebook focuses on classifying fashion images using Convolutional Neural Networks.

Key areas covered:

- Loading and exploring the Fashion-MNIST dataset.
- Image preprocessing and normalization.
- Building a CNN classification model.
- Feature extraction using convolutional layers.
- Applying pooling and activation functions.
- Training and evaluating the model.
- Analyzing classification results.

### 4. `CUSTOM.ipynb`
**Custom Dataset Image Classification**

This notebook demonstrates image classification using a custom dataset, focusing on applying deep learning techniques to real-world image data.

Key areas covered:

- Loading and preprocessing custom image datasets.
- Organizing image data and class labels.
- Image resizing and normalization.
- Data augmentation.
- Applying transfer learning.
- Using pretrained CNN architectures.
- Training and evaluating the custom image classification model.

**Custom Dataset:** Dice Face Images Classification and Recognition.

Dataset Link: https://www.kaggle.com/datasets/abdulwahib480/dice-face-images-classification-and-recognition

## Datasets

The practical implementations explore the following datasets:

| Dataset | Purpose | Classification Type |
|---|---|---|
| CIFAR-10 | General object image classification | Multi-Class |
| Fashion-MNIST | Clothing and fashion image classification | Multi-Class |
| Dice Face Images | Custom image classification and recognition | Multi-Class |

### External Dataset Resource

The custom dice image dataset is available on Kaggle:

[Dice Face Images Classification and Recognition – Kaggle](https://www.kaggle.com/datasets/abdulwahib480/dice-face-images-classification-and-recognition)

## CNN Concepts and Techniques

**1. Convolution**

Extracts important visual features from images using learnable filters and kernels.

**2. Pooling**

Reduces the spatial dimensions of feature maps while retaining important information.

**3. Padding and Stride**

Control the spatial dimensions and movement of convolution filters during feature extraction.

**4. Batch Normalization**

Normalizes intermediate layer activations to support stable and efficient model training.

**5. Dropout**

Helps reduce overfitting by randomly disabling neurons during training.

**6. Transfer Learning**

Uses pretrained neural network architectures to adapt learned image features to a new classification task.

**7. Data Augmentation**

Applies transformations to training images to improve model generalization.

## CNN Architectures

The theoretical and practical learning covers the following architectures:

- LeNet
- VGG
- ResNet
- Custom CNN Architectures
- Pretrained CNN Models for Transfer Learning

## Technologies and Libraries

- Python
- PyTorch / TensorFlow
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook
- Google Colab

## How to Run

1. Clone or download this repository.

2. Navigate to the Week 2 directory.

3. Install the required libraries:

   ```bash
   pip install torch torchvision numpy pandas matplotlib scikit-learn
   ```

4. Open Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open the required notebook:
   - `CIFAR10.ipynb`
   - `Fashin_MNIST.ipynb`
   - `CUSTOM.ipynb`

6. Download the custom dice dataset from Kaggle and configure its dataset path according to the notebook.

7. Execute the notebook cells sequentially.

Alternatively, upload the notebooks to Google Colab and run them using a suitable runtime.

## Week 2 Checkpoint Evaluation

- Build a CNN model from scratch for image classification.
- Implement image classification using CIFAR-10 or Fashion-MNIST.
- Apply Batch Normalization and Dropout.
- Perform image augmentation.
- Experiment with transfer learning on a custom dataset.
- Evaluate model performance and visualize classification results.

---

**Phase:** 02 – Convolutional Neural Networks  
**Week:** 02  
**Duration:** 1–1.5 Weeks  
**Focus:** CNN Architecture & Image Classification  
**Framework:** PyTorch / TensorFlow  
**Language:** Python  
**Environment:** Jupyter Notebook / Google Colab