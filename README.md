<div align="center">

# Mostafa Samer
**Machine Learning Engineer · Computer Vision**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/mostafa-samer)
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=flat&logo=kaggle&logoColor=white)](https://kaggle.com/mstfasmir)
[![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)](https://huggingface.co/mstfasmir)

</div>

---

Final-year Computer Science student at Zagazig University (Graduation: June 2026), specializing in deep learning for medical imaging and production ML deployment. I build systems end-to-end — from dataset construction and training on Kaggle T4/P100 GPUs, to ONNX export and FastAPI/HuggingFace Spaces deployment.

Current focus: vision-language models for clinical dermatology and multi-modal AI in low-resource Egyptian healthcare settings.

---

## Featured Projects

### 🔬 Skin Disease Classifier — 97.47% TTA Accuracy
**35-class, 262K-image dermatology classifier using Swin-Base transformer**
- Solved JPEG decode bottleneck via LMDB → reduced epoch time from ~3000s to ~180s
- 7-phase progressive layer unfreezing with SAM optimizer + SWA + MixUp + FocalLoss
- Deployed to HuggingFace Spaces as `skin-scan-v2`: FastAPI backend, ONNX Runtime inference, GradCAM visualization, TTA, prediction logging
- ONNX weights hosted at [`mstfasmir/skin-scan-weights`](https://huggingface.co/mstfasmir/skin-scan-weights)

`PyTorch` `timm` `Swin-Base` `ONNX Runtime` `FastAPI` `HuggingFace Spaces`

---

### 🎥 Football Match Analysis Pipeline
**Tactical analysis system for broadcast footage**
- YOLOv8-m + ByteTrack player tracking · KMeans jersey team classification · Pitch homography for tactical coordinate mapping
- Exports structured data for Tableau visualization
- Targets Kaggle T4 GPU with public Roboflow + DFL Bundesliga datasets

`YOLOv8` `ByteTrack` `OpenCV` `Homography` `KMeans`

---

### 🐆 Jaguar Individual Re-Identification (Kaggle Competition)
- Swin-Small (0.86 LB) → ConvNeXtV2-Base pipeline
- Diagnosed critical RGBA→RGB conversion bug corrupting pixel values across train/inference

`timm` `ConvNeXtV2` `Metric Learning`

---

## Stack

| Domain | Tools |
|---|---|
| **Modeling** | PyTorch · timm · HuggingFace Transformers · scikit-learn |
| **CV** | Swin Transformer · ConvNeXt · YOLOv8 · OpenCV · LMDB |
| **Optimization** | SAM · SWA · FocalLoss · EMA · MixUp · AMP |
| **Deployment** | ONNX Runtime · FastAPI · HuggingFace Spaces · Streamlit |
| **Training Infra** | Kaggle (T4/P100) · DDP · WeightedRandomSampler |
| **Languages** | Python · C++ |

---

## Certifications

NVIDIA Deep Learning · ITI · NTI · Huawei ICT

---

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=mstfasmir&show_icons=true&hide_border=true&theme=default&hide=stars&count_private=true)

</div>
