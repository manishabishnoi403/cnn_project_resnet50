# CIFAR-10 Classification with ResNet50

This project applies **transfer learning with ResNet50** to classify images from the **CIFAR-10 dataset** into 10 categories.  
The implementation is provided in a single **Jupyter Notebook** for simplicity.

---

## 📌 Project Overview
- **Dataset:** CIFAR-10 (60,000 images across 10 classes)
- **Model Backbone:** ResNet50 pre-trained on ImageNet
- **Fine-tuning:** Last 20 layers unfrozen
- **Image Size:** Resized to 128×128
- **Techniques Used:**
  - Data augmentation (flip, brightness, contrast, saturation, hue)
  - Mixed precision training
  - EarlyStopping & ReduceLROnPlateau callbacks

---

## 🚀 Results
- Achieved **~89% test accuracy** (update after training).
- Notebook includes:
  - Training process with augmentations
  - Validation accuracy & loss curves
  - Final evaluation on CIFAR-10 test set

---

## 🛠️ How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/manishabishnoi403/cnn_project_resnet50.git
   cd cnn_project_resnet50
