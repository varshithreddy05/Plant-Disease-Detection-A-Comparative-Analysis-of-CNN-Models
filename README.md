README - Plant-Disease-Detection-A-Comparative-Analysis-of-CNN-Models
This repository implements plant disease detection using transfer learning and custom CNN models.

Models Used:

EfficientNetB0:
Training Accuracy: 99.4%
Validation Accuracy: 98.4%
Pretrained on ImageNet; Resized to 224x224; Added dense and dropout layers.

ResNet50:
Training Accuracy: 99.8%
Validation Accuracy: 97.7%
Pretrained on ImageNet; Custom classification layers added.

InceptionV3:
Training Accuracy: 65.9%
Validation Accuracy: 63.6%
Image resolution: 299x299; Regularized via Dropout.

Custom CNN:
Training Accuracy: 97.8%
Validation Accuracy: 94.5%
Five convolutional layers; Dropout layers for overfitting reduction.

Best Model:
EfficientNetB0 delivers the highest accuracy with excellent generalization, making it the most effective model for plant disease classification.
