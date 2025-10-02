# forest-fire-detection-deep-learning
A deep learning-based image classification model to detect the presence of forest fires in satellite and surveillance images using Convolutional Neural Networks (CNNs).

Features:
Binary classification: fire vs. no fire

Trained with CNN using TensorFlow/Keras

Image preprocessing and data augmentation

Achieved ~80% test accuracy

Visualization of predictions with matplotlib

Technologies Used: Python, TensorFlow / Keras, NumPy, Matplotlib, Jupyter Notebook

Dataset

This project uses The Wildfire Dataset, which contains labeled images of fire and no fire conditions.

Downloaded using kagglehub

Path: /kaggle/input/the-wildfire-dataset


# Advanced Model: EfficientNet + Grad-CAM

A deep learning-based image classification model to detect the presence of forest fires in satellite and surveillance images using EfficientNet (transfer learning) and Grad-CAM visualization.

Features:

Binary classification: fire vs. no fire

Transfer learning with EfficientNetB0 (pretrained on ImageNet)

Fine-tuned classifier with Dense and Dropout layers

Image preprocessing and data augmentation

Achieved ~88–90% test accuracy

Grad-CAM heatmap visualization for model interpretability

Misclassified images analyzed to understand error patterns

Technologies Used:

Python

TensorFlow / Keras

EfficientNet

NumPy

Matplotlib, Seaborn

OpenCV (for Grad-CAM overlays)

Jupyter Notebook

Dataset
This project uses The Wildfire Dataset, which contains labeled images of fire and no fire conditions.

Downloaded using kagglehub

Path:

/kaggle/input/the-wildfire-dataset

