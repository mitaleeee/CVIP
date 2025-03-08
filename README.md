# Multi-Class Abnormality Classification - Capsule Vision 2024  

This project tackles **multi-class abnormality classification** for the **Capsule Vision 2024 dataset** using **ResNet152V2, EfficientNetV2M, and an Ensemble model** to assist gastroenterologists in reducing analysis time while maintaining high diagnostic accuracy.  

---

## **Models Implemented**
### ResNet152V2  
- Pretrained on **ImageNet**  
- Uses **skip connections** to tackle vanishing gradients  
- Extracts deep visual features for classification  

### EfficientNetV2M  
- Utilizes **fused-MBConv layers** for efficient computations  
- Optimized for **speed & memory efficiency**  

### Ensemble Model  
- Merges **ResNet152V2 and EfficientNetV2M** feature maps  
- Uses **GELU activation** and **dropout** for better generalization  
- Improves **classification accuracy** for medical imaging  

---
