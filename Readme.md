# Medical Segmentation & Image Classification with Deep Learning 🧠🐶🐱

This repository contains two deep learning projects:

1. **Lung Segmentation** using a custom Residual U-Net
2. **Cats vs Dogs Image Classification** using InceptionResNetV2

---

## 🫁 Lung Segmentation - Residual U-Net

### 🔍 Overview
- **Goal**: Segment lung regions in chest X-ray images
- **Model**: U-Net with residual blocks
- **Input Size**: 512×512 (grayscale)
- **Output**: Binary mask (lung area)

### ⚙️ Highlights
- Residual connections for deeper representation
- Encoder-decoder structure (U-Net)
- Sigmoid activation for binary segmentation
- Visual predictions under multiple thresholds

### 🧪 Training
- **Loss**: Binary Crossentropy
- **Optimizer**: Adam
- **Metric**: Accuracy
- **Epochs**: 20+

### 📈 Outputs
- Training/Validation accuracy
- Segmentation masks
- Threshold-wise visual comparisons

---

## 🐱🐶 Cats vs Dogs Classification - InceptionResNetV2

### 🔍 Overview
- **Goal**: Classify images as either cat or dog
- **Model**: InceptionResNetV2 (transfer learning)
- **Dataset**: Standard labeled dataset (e.g., Kaggle Dogs vs Cats)
- **Input Size**: 180×180 (RGB)

### ⚙️ Highlights
- Pre-trained base model (InceptionResNetV2)
- Custom classification head
- Data augmentation applied during preprocessing
- Fast convergence using fine-tuning

### 🧪 Training
- **Loss**: Binary Crossentropy
- **Optimizer**: Adam
- **Metric**: Accuracy
- **Epochs**: ~10–15 (depending on dataset size)

### 📊 Evaluation
- Accuracy & loss plots
- Sample predictions with true labels

---

## 🔧 Requirements

- Python 3.x
- TensorFlow 2.x
- Matplotlib, NumPy, and other common packages


📬 Contact Me
I'm always open to collaboration, feedback, or just a friendly conversation!

📧 Email: (yasminkadry6720@gmail.com)

💼 LinkedIn:(https://www.linkedin.com/in/yasmin-kadry/)

💻 GitHub:(https://github.com/yasminkadry)