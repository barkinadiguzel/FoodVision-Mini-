# 🍕 FoodVision Mini — PyTorch Implementation

> **EfficientNetB2-based image classifier trained on 20% of the Food-101 dataset to distinguish between pizza, steak, and sushi using PyTorch.**

An image classification project built with **PyTorch**, designed to distinguish between **pizza**, **steak**, and **sushi** images using an **EfficientNetB2** architecture.  
Only **20% of the original Food-101 dataset** was used to train this compact yet effective model.
[Download the model](https://huggingface.co/spaces/Barkins/Food_Vision_Mini/blob/main/09_pretrained_effnetb2_feature_extractor_pizza_steak_sushi_20_percent.pth)
---

## 🧠 Overview

This project demonstrates how a small subset of data can still yield strong results when combined with efficient architectures.  
The model is lightweight, quick to train, and performs well on limited data.

### Key Features
- Implemented entirely with **PyTorch**
- 3-class classification: 🍕 **Pizza**, 🥩 **Steak**, 🍣 **Sushi**
- Uses **EfficientNetB2** as the feature extractor
- Trained on only **20%** of the Food-101 dataset
- Includes scripts for training, validation, and inference
- Ready for deployment or further fine-tuning

---

## 🧩 Requirements

Install dependencies before running the project:

```bash
pip install torch torchvision torchaudio
pip install matplotlib
pip install numpy
pip install tqdm
pip install torchinfo
pip install pillow
```
## Feedback
For feedback or questions, contact: [barkin.adiguzel@gmail.com](mailto:barkin.adiguzel@gmail.com)
