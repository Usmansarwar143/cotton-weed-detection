<h1 align="center">🌿 Cotton Weed Detection using YOLOv8</h1>

<p align="center">
  An AI-powered cotton weed classification system built using YOLOv8 Classification (YOLOv8-cls).<br/>
  Designed to assist precision agriculture by automatically identifying cotton crops and common weeds from field images.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/YOLOv8-Ultralytics-111827?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/OpenCV-Computer_Vision-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white"/>
  <img src="https://img.shields.io/badge/TensorFlow_Lite-Mobile_AI-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white"/>
  <img src="https://img.shields.io/badge/Precision_Agriculture-AI-green?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/License-MIT-22c55e?style=for-the-badge"/>
</p>

---

## 📌 Overview

Cotton farming is highly affected by weed infestation, which reduces crop yield and increases production costs. Manual weed identification is time-consuming and requires agricultural expertise.

This project presents an **AI-based Cotton Weed Detection System** developed using **YOLOv8 Classification (YOLOv8-cls)** to automatically classify field images into:

- 🌱 Cotton Crop
- 🌿 Black Pigweed (*Trianthema portulacastrum*)
- 🌾 Nutgrass (*Cyperus rotundus*)

The trained model achieves high classification performance and serves as the core AI engine behind both a web-based research showcase and a Flutter mobile application for real-world deployment.

---

## 🎯 Objectives

- Automate cotton weed identification
- Support precision agriculture practices
- Reduce manual monitoring efforts
- Enable real-time weed classification on mobile devices
- Provide a foundation for future smart farming solutions

---

## ⚙️ Model Pipeline

| Step | Stage | Description |
|--------|---------|-------------|
| 1 | Dataset Collection | CottonWeeds dataset acquired from Kaggle |
| 2 | Data Preparation | Image preprocessing and dataset organization |
| 3 | Model Training | YOLOv8 Classification model trained on labeled images |
| 4 | Evaluation | Performance analysis using validation and test datasets |
| 5 | Deployment | Integration into Web Platform and Flutter Mobile App |

---

## 📊 Dataset Information

| Property | Details |
|----------|---------|
| Source | CottonWeeds Dataset (Kaggle) |
| Total Images | 7,578 |
| Classes | Cotton Crop, Black Pigweed, Nutgrass |
| Model Type | YOLOv8 Classification (YOLOv8-cls) |
| Input Size | 224 × 224 RGB |
| Framework | Ultralytics YOLOv8 |

### Class Labels

| Class ID | Class Name |
|----------|-----------|
| 0 | Black Pigweed |
| 1 | Cotton Crop |
| 2 | Nutgrass |

---

## 📈 Model Performance

The repository includes:

- Confusion Matrix
- Classification Report
- Training & Validation Loss Curves
- Epoch-wise Performance Analytics
- Sample Predictions
- Best Model Weights

Performance visualizations can be found in:

```text
classification_report.jpeg
confusion_matrix.jpeg
loss_curves.jpeg
training_val_loss_curves.jpeg
interactive_performance_analytics.jpeg
best_epoch_details.jpeg
best_model_epoch.jpeg
```

---

## 📁 Repository Structure

```text
Cotton-Weed-Detection/
│
├── Dataset/                           # Dataset directory
│
├── cottonweed.ipynb                   # Training & evaluation notebook
│
├── best.pt                            # Best trained YOLOv8 model
│
├── classification_report.jpeg         # Classification metrics
├── confusion_matrix.jpeg              # Confusion matrix
├── loss_curves.jpeg                   # Training loss visualization
├── training_val_loss_curves.jpeg      # Training vs validation loss
├── best_epoch_details.jpeg            # Best epoch statistics
├── best_model_epoch.jpeg              # Best model information
├── interactive_performance_analytics.jpeg
│
├── output1.png                        # Sample prediction
├── output2.png                        # Sample prediction
├── output3.png                        # Sample prediction
├── output4.png                        # Sample prediction
│
└── README.md
```

---

## 🚀 Getting Started

### Clone Repository

```bash
git clone https://github.com/Usmansarwar143/cotton-weed-detection.git
cd cotton-weed-detection
```

### Create Environment

```bash
python -m venv venv
```

Activate:

```bash
# Windows
venv\Scripts\activate

# Linux/Mac
source venv/bin/activate
```

### Install Dependencies

```bash
pip install ultralytics
pip install torch torchvision
pip install opencv-python
pip install matplotlib
pip install seaborn
pip install pandas
pip install scikit-learn
```

### Run Notebook

```bash
jupyter notebook cottonweed.ipynb
```

---

## 📷 Sample Predictions

Example prediction outputs are included in:

```text
output1.png
output2.png
output3.png
output4.png
```

Each prediction displays:

- Predicted Class
- Confidence Score
- Model Inference Result

---

## 🔗 Related Projects

This repository contains the core AI model used across multiple deployment platforms.

| Repository | Description |
|------------|-------------|
| **Cotton Weed Detection (This Repository)** | YOLOv8 training, evaluation, and model assets |
| **Cotton Weed Detection Website** | Research showcase web platform |
| **Cotton Weed Detection Flutter App** | Mobile application with on-device AI inference |

### Website Repository

Replace with your repository:

```text
https://github.com/Usmansarwar143/Cotton-weed-detection-website
```

### Flutter App Repository

Replace with your repository:

```text
https://github.com/Usmansarwar143/Cotton-weed-detection-app
```

---

## 👥 Team

| Name | Role | Links |
|--------|--------|--------|
| **Muhammad Usman Sarwar** | AI/ML Developer | [GitHub](https://github.com/Usmansarwar143) · [LinkedIn](https://www.linkedin.com/in/muhammad-usman-018535253) |
| **Sibgha Mursaleen** | AI/ML Developer | [GitHub](https://github.com/SibghaMursaleen) · [LinkedIn](https://www.linkedin.com/in/sibgha-mursaleen-4567aa253) |

**Institution:** Sukkur IBA University  
**Department:** BE Computer Systems Engineering

---

## 🎓 Academic Contribution

This project was developed as part of academic research in the field of:

- Artificial Intelligence
- Computer Vision
- Deep Learning
- Precision Agriculture

The work demonstrates how lightweight deep learning models can be used to support smart farming and agricultural automation.

---

## 📄 Licenses

Released under the MIT License.

---

<p align="center">
  Built with 🌿 YOLOv8 · Python · Computer Vision · Sukkur IBA University
</p>
