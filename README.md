# Pneumonia Detection using EfficientNet 🩺📊

## 📌 Introduction
This project implements **Deep Learning-based Pneumonia Detection** using **EfficientNet** on **Chest X-ray images**. The model is built using **transfer learning** and fine-tuned to classify chest X-rays into **normal** and **pneumonia** categories. The implementation is based on the research paper: *Automated Diagnosis of Pneumonia from Classification of Chest X-ray Images using EfficientNet*.

## 🚀 Features
- **Dataset Handling**:
  - Chest X-ray dataset downloaded from **Kaggle**.
  - Balanced train-validation-test split using **StratifiedShuffleSplit**.
- **Data Preprocessing & Augmentation**:
  - Image resizing to **128×128** pixels.
  - **Data augmentation techniques**: Rotation, width & height shift, horizontal flipping, zoom.
  - Addressing **class imbalance** using `compute_class_weight`.
- **Deep Learning Model**:
  - Utilization of **EfficientNetB2** for feature extraction.
  - Custom **CNN classifier** with `GlobalAveragePooling2D`, `Dense`, `Dropout`, and `BatchNormalization` layers.
- **Training Optimization**:
  - Optimized with `Adam` optimizer and `LearningRateScheduler`.
  - `EarlyStopping` and `ModelCheckpoint` for training efficiency.
- **Model Evaluation**:
  - **Confusion Matrix, Precision, Recall, F1-score, and AUC (Area Under Curve)**.
  - Performance visualization with **accuracy and loss curves, ROC, and precision-recall curves**.

## 📂 Project Structure
```
📦 Pneumonia-Detection-EfficientNet
├── 📜 _machine_vision_.ipynb    # Jupyter Notebook with full implementation
├── 📜 Automated_Diagnosis_of_Pneumonia_from_classification_of_Chest_X.pdf  # Reference research paper
├── 📜 README.md                 # Project documentation
```

## 📌 How to Run
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook _machine_vision_.ipynb
   ```
2. Run all cells sequentially to execute data preprocessing, model training, and evaluation.

## 📊 Results Analysis
- **Performance Metrics**: Accuracy, Precision, Recall, F1-score.
- **Confusion Matrix**: Understanding correct and incorrect predictions.
- **Grad-CAM Visualization**: Interpreting model decisions using heatmaps.

## 📧 Contact
For any inquiries or collaboration opportunities, reach out to:
📩 Email: emad.k50000@gmail.com

## ⭐ Contribute
Feel free to fork this repository, report issues, or submit pull requests to improve the project.

🔹 **Developed by Emad K | Open Source & Research-Oriented**

