# 🩺 Diabetic Retinopathy Detection

A deep learning project for detecting **diabetic retinopathy (DR)** from retinal fundus images. This pipeline includes image preprocessing, data augmentation, and classification using convolutional neural networks (CNNs) to predict DR severity levels.

---

## 🚀 Features

* Preprocessing of fundus images for better feature extraction.
* Data augmentation techniques to increase model robustness.
* CNN-based classification of DR into severity levels.
* Easy-to-understand pipeline suitable for research and educational purposes.

---

## ▶️ Usage

### 1) Filter Fundus Images by Quality

Use the notebook to keep only good and usable quality images, and discard low-quality ones:

```bash
./Image Quality Filtering/Image_Quality_Filtering.ipynb
```

### 2) Preprocess and Train the Model

Run the notebook for image preprocessing, data augmentation, and CNN model training:

```bash
./DR_detection/DR_detection.ipynb
```

- You can adjust preprocessing parameters and training settings directly in the notebook.


---

## 🎯 Objectives

* Detect diabetic retinopathy automatically from retinal images.
* Provide an end-to-end pipeline for medical image classification using deep learning.
* Help researchers and developers understand medical image preprocessing and CNN-based classification.

---

## 📚 References

* [Kaggle Diabetic Retinopathy Dataset](https://www.kaggle.com/datasets/ascanipek/eyepacs-aptos-messidor-diabetic-retinopathy)
* [PyTorch Documentation](https://pytorch.org/docs/stable/index.html)


