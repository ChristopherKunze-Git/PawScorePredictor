# PetFinder Pawpularity Contest - Deep Learning Models

This repository contains the code and models used for the [Kaggle PetFinder.my - Pawpularity Contest](https://www.kaggle.com/competitions/petfinder-pawpularity-score). The goal of this challenge is to predict the **Pawpularity Score** of pet images based on their visual features.

## Models and Methods Used

The project explores multiple deep learning architectures for feature extraction and regression, including:

- **Convolutional Neural Networks (CNN)**
- **Multilayer Perceptron (MLP)**
- **Vision Transformer (ViT)**
- **Data-efficient Image Transformer (DeiT)**
- **Swin Transformer**
- **OpenAI CLIP Model**

Among these, **ViT (Vision Transformer)** achieved the best performance in predicting the Pawpularity Score.

## Repository Structure
📂 PAWSCOREPREDICTOR
│-- 📂 Baseline_Model/
│   │-- image.png
│   │-- README.md
│
│-- 📂 Data_Augmentation/
│   │-- data_augmentation.ipynb
│
│-- 📂 Dataset_Characteristics/
│   │-- exploratory_data_analysis.ipynb
│
│-- 📂 Literature_Review/
│   │-- 1512.03385v1.pdf
│   │-- 2010.11929v2.pdf
│   │-- 2012.12877v2.pdf
│   │-- 2103.14030v2.pdf
│   │-- README.md
│
│-- 📂 Model/
│   │-- pawpularity_deit.ipynb
│   │-- pawpularity-cnn-mlp.ipynb
│   │-- PawScoreModels.ipynb
│   │-- plots.ipynb
│
│-- 📂 Presentation/
│   │-- Final Presentation ML.pptx
│   │-- README.md


## Installation

Clone the repository and install dependencies:

git clone https://github.com/ChristopherKunze-Git/PawScorePredictor.git
cd PetFinder-Pawpularity
pip install -r requirements.txt

### Results Achieved
![alt text](image.png)


## Acknowledgments
1. Kaggle for providing the dataset and competition platform.
2. Hugging Face Transformers for pre-trained ViT, DeiT, and Swin models.
3. OpenAI for the CLIP model.


### Authors
1. Christopher Kunze
2. Khushi Kala