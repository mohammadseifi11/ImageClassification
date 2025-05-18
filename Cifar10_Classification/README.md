## 📄 Abstract

This project explores the training and interpretability of a **Convolutional Neural Network (CNN)** on the **CIFAR-10 dataset**, with a strong emphasis on **visualization over performance**. While the model achieves a validation accuracy of ~85%, the primary goal is to demonstrate **what you can visualize before, during, and after training** to better understand how CNNs learn.

The repository includes code and examples for visualizing:
- **Data distribution and augmentation**
- **Training dynamics** (accuracy & loss curves)
- **Learned filters** in convolutional layers
- **Activation maps** showing feature responses
- **Model evaluation metrics** like confusion matrices and misclassified samples

 This is an excellent resource for anyone looking to go beyond model accuracy and dive into **how CNNs process images and what they learn at different stages**.

 # Clone the repo
git clone https://github.com/mohammadseifi11/ImageClassification.git
cd Cifar10_Classification

# Install dependencies
pip install -r requirements.txt

## 📦 Pretrained Model

A trained version of the CNN model (`cifar10_model.h5`) is available https://drive.google.com/file/d/1CNw-7CIXi0cuX3qMleE66WT8u6qLSnI9/view?usp=drive_link (approx. 27 MB).

To use it:
1. Download and place it in the `models/` directory.
2. Run inference or continue training from this checkpoint.
