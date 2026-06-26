# CNN-project-
# 🧠 Brain Tumor MRI Classification using CNN

A Deep Learning project that classifies Brain MRI images into different tumor categories using a Convolutional Neural Network (CNN). The model is built with TensorFlow/Keras and trained on a publicly available MRI dataset from Kaggle.

---

## 📌 Project Overview

Brain tumor diagnosis from MRI scans is a challenging and time-consuming task. This project uses a Convolutional Neural Network (CNN) to automatically classify MRI images into different brain tumor categories, assisting in faster and more accurate diagnosis.

The model performs image preprocessing, training, prediction, and evaluation on MRI images.

---

## 🚀 Features

- MRI image preprocessing and normalization
- Multi-class brain tumor classification
- CNN model built from scratch
- TensorFlow/Keras implementation
- Model training and validation
- Predict tumor class from a new MRI image
- Visualization of prediction results

---

## 🗂 Dataset

**Dataset:** Brain Tumor MRI Dataset

Source:
https://www.kaggle.com/datasets/deeppythonist/brain-tumor-mri-dataset

### Classes

- Glioma
- Meningioma
- Pituitary
- No Tumor

---

## 🛠 Tech Stack

- Python
- TensorFlow
- Keras
- NumPy
- OpenCV
- Matplotlib
- Google Colab

---

## 📁 Project Structure

```
Brain-Tumor-CNN/
│
├── CNN_MRI_MODEL.ipynb
├── README.md
├── images/
│     ├── prediction_example.png
│     └── architecture.png
├── requirements.txt
└── model/
      └── trained_model.h5
```

---

## ⚙️ Model Architecture

The CNN consists of multiple convolutional and max-pooling layers followed by fully connected dense layers.

Architecture:

- Conv2D (ReLU)
- MaxPooling2D
- Conv2D (ReLU)
- MaxPooling2D
- Conv2D (ReLU)
- MaxPooling2D
- Flatten
- Dense Layer
- Output Layer (Softmax)

---

## 🔄 Workflow

1. Download MRI dataset
2. Load training and testing images
3. Normalize image pixel values
4. Build CNN model
5. Train the model
6. Evaluate model performance
7. Predict tumor class on unseen MRI images

---

## 📊 Image Preprocessing

- Image resizing (256 × 256)
- Pixel normalization
- Dataset batching
- TensorFlow Dataset API

---

## 🧪 Model Training

Loss Function:

```
Sparse Categorical Crossentropy
```

Optimizer:

```
Adam
```

Evaluation Metric:

```
Accuracy
```

---

## 🔍 Prediction Example

Input:

```
MRI Image
```

Output:

```
Predicted Class:
Glioma
```

*(Prediction depends on the input image.)*

---

## 📦 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Brain-Tumor-CNN.git
```

Go to project folder

```bash
cd Brain-Tumor-CNN
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the notebook

```bash
jupyter notebook
```

or open it directly in Google Colab.

---

## 📈 Future Improvements

- Apply Transfer Learning (EfficientNet, ResNet50)
- Hyperparameter tuning
- Data augmentation
- Early stopping and model checkpointing
- Deploy using Streamlit or Flask
- Convert model into a web application
- Explain predictions using Grad-CAM

---

## 💡 Skills Demonstrated

- Deep Learning
- Computer Vision
- CNN Architecture
- Image Classification
- TensorFlow/Keras
- OpenCV
- Data Preprocessing
- Model Evaluation
- Python Programming

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Open a Pull Request

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Yug Sharma**

- GitHub: https://github.com/yourusername
- LinkedIn: https://linkedin.com/in/yourprofile

If you found this project useful, consider giving it a ⭐ on GitHub.
