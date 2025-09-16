# AI Storytelling: CIFAR-100 Image Classification  

## 📌 Project Overview  
This project applies **Artificial Intelligence (AI) techniques** to the **CIFAR-100 dataset**, a challenging benchmark of 60,000 color images across 100 classes.  
We build and compare two models — an **Artificial Neural Network (ANN)** and a **Convolutional Neural Network (CNN)** — to analyze how architecture choice impacts performance in image classification tasks.  

## 📊 Key Insights from Analysis  
- **Dataset**: 60,000 images (32×32 pixels, 3 channels), 100 balanced classes  
- **Preprocessing**: Normalization and one-hot encoding applied  
- **Model Comparison**:  
  - **ANN** (flattened pixel input): Accuracy ~20–30%  
  - **CNN** (spatial feature extraction): Accuracy ~40–60%+  
- **Visualization**: Training curves, confusion matrix (sampled), and prediction examples  
- **Takeaway**: CNNs significantly outperform ANNs on image datasets by leveraging spatial patterns (edges, textures, shapes).  

## 📂 Repository Contents  
- `CIFAR100-ANN-vs-CNN.ipynb` → Full workflow: dataset setup, preprocessing, ANN & CNN models, training, evaluation, and visualizations  
- Training history plots for accuracy/loss  
- Confusion matrix heatmaps  
- Sample prediction visualizations  
- ANN vs CNN comparison table & bar chart  

## 🔮 Next Steps  
Future improvements and extensions could include:  
- **Data Augmentation** (rotations, flips, shifts) to improve CNN generalization  
- **Transfer Learning** with pre-trained models like ResNet or VGG for higher accuracy  
- **Hyperparameter Tuning** (filters, kernel size, dropout, optimizers) for performance optimization  
- **Explainable AI** methods (e.g., Grad-CAM) to visualize what the CNN focuses on in images  

---
