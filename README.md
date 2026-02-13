# medicinal_plant_identification-_using_VIT

# Overview

This project presents a deep learning–based plant species identification system using leaf images. The proposed framework utilizes the Vision Transformer (ViT) architecture to capture global contextual relationships and detailed visual patterns such as leaf shape, venation structure, and texture.

The system is designed to achieve high classification accuracy while maintaining computational efficiency, making it suitable for academic research and real-world applications.

# Objectives

Develop an automated plant species recognition system

Use Vision Transformer for feature extraction and classification

Improve classification accuracy on complex leaf datasets

Evaluate model performance using training, validation, and testing splits

# Model Architecture

The core component of the system is the Vision Transformer (ViT) model.

# Workflow:

Input leaf image

Image is divided into fixed-size patches

Patch embeddings are generated

Positional embeddings are added

Transformer encoder layers process global relationships

Classification token output is passed through a Softmax layer

Final plant species prediction is produced

# Dataset

The dataset consists of labeled plant leaf images categorized into multiple species.
Each image is manually annotated to enable supervised learning.

The dataset is divided into:
Training set
Validation set
Testing set
Note: Dataset files are not included in this repository due to size limitations.

# Technologies Used

Python,
PyTorch,
Google Colab,
NumPy,
Pandas,
Matplotlib,
Scikit-learn

# Installation

Clone the repository:
git clone https://github.com/your-username/Plant-Leaf-Identification.git
cd Plant-Leaf-Identification
Install dependencies:
pip install -r requirements.txt

# How to Run

If using Google Colab:

Upload the notebook

Mount Google Drive

Update dataset path

Run all cells

If running locally:

python train.py
Performance Evaluation
The model is evaluated using:
Accuracy,
Precision,
Recall,
F1-score,
Confusion Matrix.

The Vision Transformer model demonstrates strong generalization capability on unseen leaf samples.

# Results

The proposed system achieves high classification accuracy and effectively captures long-range dependencies in leaf structures.
( The model achieved 97.3% test accuracy.)

# Future Work

Expand dataset with additional plant species,
Apply advanced data augmentation techniques,
Deploy model as a web or mobile application

# Authors

Sarishma.ch

Divya.ch

DurgaBhavani.k

Abhishek.p

B.Tech Final Year Project
Deep Learning Based Plant Identification System
