# 🍅 Tomato Leaf Disease Classification using ViT and Inception-v3

This project compares **Vision Transformers (ViT)** and **Convolutional Neural Networks (CNN - Inception-v3)** for multi-class classification of tomato leaf diseases using the [PlantVillage dataset](https://www.mdpi.com/2073-4395/14/2/327). It was completed as part of the **Neural Networks and Deep Learning course** at the University of Tehran.

## 📌 Overview

- **Objective**: Classify 10 classes of tomato leaf images (9 diseases + 1 healthy class).
- **Main Tasks**:
  - Data preprocessing and augmentation
  - CNN model training (Inception-v3)
  - ViT model training (custom implementation)
  - Evaluation and comparison of performance
  - Patch embedding visualization

## 🛠 Tools & Libraries

- `PyTorch`, `Torchvision`, `Transformers` (HuggingFace), `PEFT`
- `Matplotlib`, `Seaborn`, `NumPy`
- `Jupyter Notebook`

## 📊 Results Summary

| Model         | Val Accuracy | Parameters | Training Time | Notes |
|---------------|--------------|------------|----------------|-------|
| Inception-v3  | ~98.0%       | ~23M       | ~90 minutes     | Pretrained |
| ViT (custom)  | ~88.0%       | ~2.5M      | ~30 minutes     | Trained from scratch |

> 🧠 The ViT model, despite being lightweight, showed competitive performance and higher efficiency in memory and training time.

## 🧪 Techniques Applied

- ✅ **Data Augmentation**:
  - Random horizontal/vertical flip
  - Color jitter, rotation, zoom
  - Gaussian blur, affine transforms
- ✅ **Patch Embedding Optimization**
- ✅ **Confusion Matrix Analysis**
- ✅ **Transfer Learning** (for Inception-v3 only)

## 🖼 Sample Visualizations

### 📈 Accuracy & Loss Curves

<p align="center">
  <img src="images/vit_accuracy_loss.png" width="400"/>
  <img src="images/cnn_accuracy_loss.png" width="400"/>
</p>

### 🔍 Confusion Matrices

<p align="center">
  <img src="images/vit_confusion_matrix.png" width="400"/>
  <img src="images/cnn_confusion_matrix.png" width="400"/>
</p>

### 🧩 Patch Embedding Visualization (ViT)

<p align="center">
  <img src="images/patch_embedding_vit.png" width="400"/>
</p>


## 📚 References

- [PlantVillage Dataset & Paper (MDPI)](https://www.mdpi.com/2073-4395/14/2/327)
- [Vision Transformer - Dosovitskiy et al.](https://arxiv.org/abs/2010.11929)

## 🧠 Authors

- **Your Name** – [your-email@example.com](mailto:your-email@example.com)  
- **Collaborator (if any)**

---

_This project was developed as part of a course assignment at the University of Tehran. For academic purposes only._



