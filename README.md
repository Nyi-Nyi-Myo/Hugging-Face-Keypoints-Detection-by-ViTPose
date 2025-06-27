# Hugging-Face Keypoints Detection by ViTPose

[![pytorch](https://img.shields.io/badge/PyTorch-2.6.0-EE4C2C.svg?style=flat&logo=pytorch)](https://pytorch.org)
[![Hugging Face](https://img.shields.io/badge/-Hugging_Face-3B4252?style=flat&logo=huggingface&logoColor=)](https://huggingface.co/)
![Static Badge](https://img.shields.io/badge/Keypoints-Detection-cyan)
![Static Badge](https://img.shields.io/badge/ViTPose-8A2BE2)

Keypoints Detection for marker pens using **ViTPose** Deep Learning Algorithm in **Hugging Face**.

## Dataset
- Marker Pens (Custom)

Annotation Type - Keypoints

Classes &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &ensp; - K, C, K

## Methodology
![Hugging Face](https://img.shields.io/badge/-HuggingFace-yellow?style=for-the-badge&logo=HuggingFace&logoColor=black&logoHeight=20)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Matplotlib](https://img.shields.io/badge/-Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)

- `"usyd-community/vitpose-base-simple"` Model
- Applied Augmentations from albumentations
- epochs = 20, Auto saving best model
- Used mse_loss and f1 for validation

## Results
- ### Validation of trained model
  
|     Train Loss    |      Val F1      |
|       -----       |      -----       |
|      0.000466     |       0.7007     |

---
⭐ Example Images results in `ViTPose_Huggingface_keypoints.ipynb`
