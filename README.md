# Prakriti-EdgeViT-Crop-Diagnosis-Mobile-App

## 📱 Overview

**Prakriti** is a mobile-based, **offline solution** for crop disease diagnosis designed to assist farmers in rural India. Many existing solutions rely on internet access or large AI models unsuitable for low-end devices.  
Our solution provides an **accurate, lightweight, and fully offline** tool that empowers farmers to detect crop diseases efficiently.

---

## 🌱 Problem Statement

Farmers face challenges in identifying crop diseases due to:
- Limited internet access in rural areas.
- Use of low-end smartphones.
- Large AI models that cannot run efficiently offline.

**Goal:**  
Develop a **compact, accurate, and offline deep learning model** to diagnose crop diseases and provide relevant farming insights.

## 🚀 Features
- Offline disease detection from leaf images  
- Confidence score for predictions  
- Expert help & crop knowledge hub  
- Fertilizer calculator (N, P, K suggestions)  
- Daily farming tips and reminders  
- PDF report generation  
- Product recommendations for crop protection
  
## 🧩 Tech Stack

- **Deep Learning Framework:** PyTorch  
- **Model:** EdgeViT-S (Vision Transformer)  
- **Programming Languages:** Python  
- **Mobile Deployment:** Android (via TorchScript `.pt`)  
- **Dataset:** PlantVillage

## ⚙️ Model Workflow
1. Image preprocessing & augmentation (resize, normalize, flip)  
2. Model training (fine-tuned EdgeViT-S)  
3. Dynamic quantization (32-bit → 8-bit)  
4. Export to `.pt` for mobile deployment  

