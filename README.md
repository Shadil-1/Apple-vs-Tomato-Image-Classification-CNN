# Apple vs Tomato Image Classification 

A Deep Learning project that uses Convolutional Neural Networks (CNN) to classify images as either Apple or Tomato.

The model is built using TensorFlow and Keras and learns visual features from fruit images to perform binary image classification.

---

## 📌 Project Overview

Image classification is one of the most common applications of Deep Learning and Computer Vision.

This project trains a CNN model to distinguish between:

- 🍎 Apple
- 🍅 Tomato

The model automatically extracts image features using convolutional layers and predicts the fruit category.

---

## 🚀 Features

- Image preprocessing and resizing
- CNN architecture implementation
- Batch Normalization
- Dropout Regularization
- Max Pooling Layers
- Model Training and Validation
- Binary Fruit Classification

---

## 🛠 Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Pillow (PIL)
- Scikit-Learn
- Jupyter Notebook

---

## 📂 Dataset

The dataset contains images from two classes:

### Classes

| Label | Fruit |
|---------|---------|
| 0 | Tomato |
| 1 | Apple |

All images are resized to:

```text
128 × 128 × 3
```

before being used for training.

---

## 🧠 CNN Architecture

### Model Structure

1. Convolution Layer (32 Filters)
2. Convolution Layer (32 Filters)
3. Dropout
4. Batch Normalization
5. Max Pooling

6. Convolution Layer (64 Filters)
7. Convolution Layer (64 Filters)
8. Dropout
9. Batch Normalization
10. Max Pooling

11. Flatten Layer
12. Dense Layer (512 Neurons)
13. Dropout
14. Output Layer (2 Classes)

---

## 📊 Training Configuration

| Parameter | Value |
|------------|---------|
| Optimizer | SGD |
| Loss Function | Binary Crossentropy |
| Epochs | 20 |
| Batch Size | 64 |
| Input Size | 128×128×3 |

---

## 🔄 Project Workflow

### Data Collection
- Load Apple and Tomato image datasets.

### Data Preprocessing
- Resize images to 128×128.
- Convert images into NumPy arrays.
- Encode labels using One-Hot Encoding.

### Train-Test Split
- 80% Training Data
- 20% Testing Data

### Model Training
- Train CNN model on fruit images.

### Evaluation
- Monitor training accuracy and validation accuracy.
- Analyze model performance.

---

## 📈 Results

The CNN model successfully learns visual patterns from the images and classifies fruits into Apple and Tomato categories.

Evaluation metrics include:

- Training Accuracy
- Validation Accuracy
- Loss Curves

---

## 📁 Project Structure

```text
FruitVision-CNN/
│
├── apple and tomato.ipynb
├── dataset/
│   ├── apples/
│   └── tomatoes/
├── README.md
└── requirements.txt
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone [https://github.com/Shadil-1/Apple-vs-Tomato-Image-Classification-CNN.git]
```

Install dependencies:

```bash
pip install tensorflow numpy pandas matplotlib pillow scikit-learn
```

Run the notebook:

```bash
jupyter notebook
```

Open:

```text
apple and tomato.ipynb
```

---

## 🔮 Future Improvements

- Increase dataset size.
- Add Data Augmentation.
- Use Transfer Learning (VGG16, ResNet50, MobileNet).
- Deploy as a web application using Streamlit.
- Support multiple fruit categories.

---

## Author

Developed as a Deep Learning and Computer Vision project using Convolutional Neural Networks (CNN) for fruit image classification.
