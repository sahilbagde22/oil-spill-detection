# 🛢️ Oil Spill Detection using U-Net & DeepLabV3

This project implements **Oil Spill Detection** from satellite imagery using **semantic segmentation** with two state-of-the-art deep learning models: **U-Net** and **DeepLabV3**.  
The goal is to identify and segment oil spills in the ocean from remote sensing data, enabling **early environmental hazard monitoring and prevention**.

---

## 📌 Features
- **Two segmentation architectures:** U-Net and DeepLabV3 (ResNet backbone)
- **Binary segmentation**: Oil Spill (1) vs Background (0)
- **Data preprocessing**: Image and mask resizing, normalization
- **Training and evaluation** with:
  - Pixel accuracy
  - IoU (Intersection over Union)
  - Dice/F1 score
- **Prediction visualization** for qualitative results
- **Confusion Matrix** to analyze model performance

---

## 📂 Dataset
The project assumes you have satellite images and binary masks:
