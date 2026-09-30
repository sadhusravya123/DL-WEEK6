# VGG16 and ResNet50 Performance Comparison

## Aim

To implement and compare the performance of pre-trained **VGG16** and **ResNet50** CNN models using the CIFAR-10 dataset.

## Dataset

* Dataset: CIFAR-10
* Images used: 4,000
* Training: 3,200
* Testing: 800
* Classes: 10
* Image size: 224 × 224 × 3

## Models

* **VGG16** – ImageNet pre-trained model
* **ResNet50** – ImageNet pre-trained model

Both models use transfer learning with a custom classification layer for the 10 CIFAR-10 classes.

## Tools Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* Google Colab

## Methodology

```text
CIFAR-10
   ↓
4000 Images
   ↓
3200 Train + 800 Test
   ↓
Resize to 224 × 224
   ↓
VGG16 / ResNet50
   ↓
Classification
   ↓
Performance Comparison
```

## Evaluation

The models are compared based on:

* Accuracy
* Loss
* Training Time

## Result

VGG16 and ResNet50 were successfully implemented and evaluated on the selected CIFAR-10 dataset.
