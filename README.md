# 🌸 Transfer Learning Without Fine-tuning

## 📋 Overview
This project implements **transfer learning** using a pre-trained **MobileNetV2** model to classify flower images into 5 categories without fine-tuning the base model weights. The model leverages ImageNet pre-trained features and trains only the classification head.

## ✨ Key Features
- 🎯 **Pre-trained MobileNetV2**: Uses ImageNet weights for feature extraction
- 🔒 **Frozen Base Model**: Preserves learned features from ImageNet
- 📊 **Weights & Biases Integration**: Experiment tracking and hyperparameter optimization
- 🌼 **5-Class Flower Classification**: 
  - Daisy
  - Dandelion
  - Roses
  - Sunflowers
  - Tulips
- ⚡ **GPU-Optimized**: Uses tf.data API with prefetching and parallel processing

## 📦 Dependencies

```bash
pip install tensorflow>=2.10.0 keras>=2.10.0 matplotlib>=3.5.0 wandb>=0.13.0