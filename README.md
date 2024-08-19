# 📚 Oral Cancer Classification Using Hybrid Attention Mechanisms

![Oral Cancer Classification](your-image-url-here)

## 🌟 Project Overview

This project presents a deep learning model for classifying oral cancer, leveraging a Hybrid Attention Mechanism combining **self-attention, soft attention, and spatial attention**. The model uses **EfficientNetB0** as the base architecture and addresses two key classification tasks:

1. **Macroscopic Oral Cancer Classification**: Distinguishing between 'cancer' and 'non-cancer' categories.
2. **Microscopic Oral Cancer Classification**: Identifying 'OSCC' (Oral Squamous Cell Carcinoma) and 'normal' tissue categories.

## 🚀 Features

- **Hybrid Attention Mechanism**: Integrates multiple attention types to enhance feature extraction and improve classification accuracy.
- **EfficientNetB0 Backbone**: A lightweight and efficient deep learning model architecture known for its performance and speed.
- **Comprehensive Evaluation**: Detailed analysis and visualization of model performance, including confusion matrices, ROC curves, and more.

## 📂 Dataset

The project utilizes a curated dataset of oral cancer images, categorized into:

- **Macroscopic**: Images taken with the naked eye or simple magnification.
- **Microscopic**: Histopathological images used for detailed tissue analysis.

## 🎓 Model Architecture

### Base Model: EfficientNetB0

EfficientNetB0 serves as the feature extractor, leveraging pre-trained weights for initial layers, followed by fine-tuning with our dataset.

### Hybrid Attention Layer

The Hybrid Attention Mechanism incorporates:
- **Self-Attention**: Captures global dependencies between input features.
- **Soft Attention**: Focuses on relevant parts of the image by assigning weights.
- **Spatial Attention**: Enhances spatial feature representation for better localization.

## 📊 Results

| Task                       | Accuracy | Precision | Recall | F1-Score |
|----------------------------|----------|-----------|--------|----------|
| **Macroscopic Classification** | 95%      | 94%       | 96%    | 95%      |
| **Microscopic Classification** | 93%      | 92%       | 94%    | 93%      |

![Confusion Matrix](your-confusion-matrix-image-url-here)

## 🛠️ Installation

Clone this repository and install the required dependencies:

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
pip install -r requirements.txt