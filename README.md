# Early Detection of Oral Cancer Using Vision Transformer and Medical Image Analysis

## 📖 Overview
This project presents an AI-powered oral cancer detection system using the Vision Transformer (ViT) model. The system analyzes oral lesion and histopathological images to classify them as cancerous or non-cancerous. By leveraging self-attention mechanisms, the model captures both local and global image features, enabling accurate and reliable early-stage oral cancer detection.

## 🎯 Objectives
- Detect oral cancer at an early stage using deep learning.
- Improve classification accuracy using Vision Transformer architecture.
- Reduce false positive and false negative predictions.
- Assist healthcare professionals in clinical decision-making.

## 🚀 Features
- Vision Transformer (ViT) based classification
- Automated feature extraction
- Image preprocessing and normalization
- Patch embedding and self-attention mechanism
- High accuracy oral cancer prediction
- Medical image analysis support

## 📂 Dataset
The dataset contains oral cavity and histopathological images collected from medical repositories and publicly available sources.

### Dataset Statistics
- Total Images: 1240
- Cancer Images: 995
- Non-Cancer Images: 245
- Training Images: 744
- Validation Images: 248
- Testing Images: 248

## ⚙️ Methodology

### 1. Data Collection
Collection of oral cavity and histopathological images from medical datasets.

### 2. Image Preprocessing
- Image Resizing
- Normalization
- Noise Reduction
- Data Augmentation

### 3. Patch Embedding
Images are divided into fixed-size patches and converted into embeddings.

### 4. Vision Transformer (ViT)
The embedded patches are processed through:
- Multi-Head Self-Attention
- Feed Forward Neural Networks
- Positional Encoding

### 5. Classification
The model classifies images into:
- Cancerous
- Non-Cancerous

## 🏗️ System Architecture

Input Image
↓
Preprocessing
↓
Patch Embedding
↓
Positional Encoding
↓
Vision Transformer Encoder
↓
Multi-Head Self-Attention
↓
Classification Layer
↓
Prediction

## 📊 Results

| Model | Accuracy (%) |
|---------|------------|
| DenseNet | 89.40 |
| ResNet | 91.32 |
| EfficientNet | 90.12 |
| GoogleNet | 93.10 |
| Vision Transformer (Proposed) | 96.58 |

### Performance Metrics
- Accuracy: 96.58%
- Precision: 96%
- Recall: 95%
- F1-Score: 95.5%

## 🛠️ Technologies Used
- Python
- TensorFlow
- Keras
- OpenCV
- NumPy
- Scikit-Learn
- Matplotlib

## 📦 Installation

### Clone Repository

```bash
git clone https://github.com/your-username/oral-cancer-detection.git
cd oral-cancer-detection
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

## ▶️ Run the Project

```bash
python train.py
```

### Prediction

```bash
python predict.py
```

## 💡 Applications
- Early Oral Cancer Detection
- Medical Image Analysis
- Clinical Decision Support Systems
- Healthcare AI Research

## 🔮 Future Enhancements
- Larger and more diverse datasets
- Explainable AI using Grad-CAM
- Multimodal learning with clinical data
- Real-time hospital deployment
- Web and mobile application integration

## 👨‍💻 Author
- Dharshini S

## 📜 License
This project is licensed under the MIT License.

## ⭐ Support
If you found this project useful, please consider giving it a star on GitHub.
