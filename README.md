# 🏭 Steel Surface Defect Detection using Deep Learning

---

## 📌 Project Description
This project implements an **Automated Steel Surface Defect Detection System** using Deep Learning and Computer Vision.  
The system classifies steel surface images into defect categories using multiple deep learning architectures and compares their performance.

The project uses **Transfer Learning** with state-of-the-art CNN architectures and applies **fine-tuning strategies** to improve classification accuracy.

---

## 🎯 Problem Statement
Manual inspection of steel surfaces is:
- Time consuming  
- Error prone  
- Costly in large-scale manufacturing  

This project automates defect detection using AI-based image classification.

---

## 📂 Dataset Used
**NEU Metal Surface Defect Dataset**

Contains multiple defect classes such as:
- Cracks  
- Inclusions  
- Scratches  
- Patches  
- Pitted surfaces  
- Rolled-in scale  

Dataset is loaded from ZIP and extracted dynamically in the notebook.

---

## 🧠 Models Implemented

### 🔹 1. Custom CNN Model
- Built using Sequential API  
- Conv2D + MaxPooling + Dense Layers  
- Used as baseline model  

---

### 🔹 2. VGG16 Transfer Learning Model
- Pretrained on ImageNet  
- Top layers customized  
- Fine-tuned last layers  
- Learning rate adjusted for stability  

---

### 🔹 3. ResNet50 Transfer Learning Model
- Residual network architecture  
- Multi-stage fine-tuning  
- Progressive layer unfreezing  
- Final boosted training stage  

---

## ⚡ Advanced Techniques Used
- Transfer Learning  
- Fine Tuning  
- Mixed Precision Training (GPU Optimization)  
- Learning Rate Scheduling  
- Data Augmentation using ImageDataGenerator  

---

## 🧪 Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1 Score  
- Confusion Matrix Visualization  

---

## 📊 Model Comparison
The project compares:
- Custom CNN  
- VGG16 Fine-tuned  
- ResNet50 Fine-tuned  

Performance comparison plotted using Matplotlib.

---

## 🧠 Technologies Used
- Python  
- TensorFlow  
- Keras  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-learn  
- Transfer Learning  
- Mixed Precision Training  
- Jupyter Notebook  

---

## 📂 Project Structure
```
Steel-Surface-Defect-Detection/
│
├── steel surface defect detection.ipynb
└── README.md
```

---

## ⚙️ How to Run Project

### 🔹 Step 1 — Install Dependencies
```
pip install tensorflow numpy pandas matplotlib scikit-learn
```

---

### 🔹 Step 2 — Run Notebook
Open Jupyter Notebook and run:
```
steel surface defect detection.ipynb
```

---

### 🔹 Step 3 — Upload Dataset ZIP
Upload NEU dataset ZIP when prompted in notebook.

---

## 📊 Output
The system provides:
- Defect classification predictions  
- Confusion matrix visualization  
- Model accuracy comparison graphs  

---

## 🚀 Future Improvements
- Real-time defect detection system  
- Industrial camera integration  
- Web-based monitoring dashboard  
- Edge AI deployment  

---

## 👩‍💻 Author
**Gunda Pavani**

---


