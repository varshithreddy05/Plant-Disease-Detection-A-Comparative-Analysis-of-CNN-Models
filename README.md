# 🌿 Plant Disease Detection: A Comparative Analysis of CNN Models

🔍 Project Overview

Detects plant diseases from leaf images using CNN and transfer learning.
Compares EfficientNetB0, ResNet50, InceptionV3, and a custom CNN model.
Focuses on accuracy, generalization, and training efficiency.

🛠️ Key Features

🔹 Best Model: EfficientNetB0 achieved the highest validation accuracy.
🔹 Transfer Learning: All pretrained models used ImageNet weights.
🔹 Custom CNN: Designed with 5 convolutional layers and dropout to reduce overfitting.
🔹 Augmentation: Applied to enhance model robustness and generalization.

🧪 Dataset

High-resolution plant leaf images across multiple disease categories.
Preprocessed with resizing and normalization to match model requirements.

📊 Results Summary

| Model          | Training Accuracy | Validation Accuracy | Input Size | Notes                                |
|----------------|-------------------|---------------------|------------|--------------------------------------|
| EfficientNetB0 | 99.4%             | 98.4%               | 224x224    | Pretrained + Dense & Dropout layers |
| ResNet50       | 99.8%             | 97.7%               | 224x224    | Custom classification head          |
| InceptionV3    | 65.9%             | 63.6%               | 299x299    | Used Dropout regularization         |
| Custom CNN     | 97.8%             | 94.5%               | 224x224    | 5 Conv layers + Dropout             |

✅ Key Takeaways

🌟 EfficientNetB0 offers the best balance of performance and generalization.
🔍 ResNet50 is competitive but slightly less accurate than EfficientNet.
📉 InceptionV3 underperformed due to possible overfitting or incompatible architecture.
🧪 Custom CNN performs well with fewer parameters but doesn't match transfer models.

🧠 Conclusion

EfficientNetB0 is the most effective model for plant disease detection in this study. It combines high accuracy, generalization ability, and low computational cost—making it suitable for practical deployment in agriculture tech solutions.
