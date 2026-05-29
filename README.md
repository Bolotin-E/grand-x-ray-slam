# Grand X-Ray Slam

🩻 Deep learning computer vision project focused on multi-label chest X-ray classification using EfficientNet-B0 and PyTorch Lightning.

Best Kaggle Public Score: **0.9216 ROC-AUC**

---

# Project Overview

This project explores automated detection of thoracic diseases from chest X-ray images using transfer learning and deep learning techniques.

The goal is to predict multiple thoracic conditions from a single chest X-ray image.

The analysis includes:

- image preprocessing
- transfer learning
- multi-label classification
- patient-level validation split
- model evaluation using ROC-AUC

---

# Dataset

Competition:

Grand X-Ray Slam: Division A

Dataset characteristics:

- chest X-ray images
- multi-label classification
- 14 thoracic disease classes
- real-world medical imaging data

Target conditions include:

- Atelectasis
- Cardiomegaly
- Consolidation
- Edema
- Pleural Effusion
- Pneumothorax
- Support Devices
- and others

---

# Technologies & Tools

- Python
- PyTorch
- PyTorch Lightning
- timm
- EfficientNet-B0
- Pandas
- NumPy
- scikit-learn
- PIL

---

# Model Architecture

Base model:

EfficientNet-B0

Training features:

- transfer learning
- weighted BCE loss
- mixed precision training
- patient-level validation split
- multi-label classification

---

# Model Performance

Evaluation Metric:

ROC-AUC

Results:

- Best Kaggle Public Score: **0.9216**
- Multi-label prediction of 14 thoracic conditions

---

# Key Features

- Medical image classification
- Deep learning workflow
- Transfer learning
- EfficientNet architecture
- Patient-level validation strategy
- Multi-label disease detection

---

# Future Improvements

Possible next steps:

- Grad-CAM explainability
- Model ensembling
- Test-time augmentation
- EfficientNet-B3/B4 comparison
- DeBERTa-style multimodal approaches

---

# Results

The project demonstrates how transfer learning and modern computer vision architectures can be applied to real-world medical imaging problems and achieve strong predictive performance.
