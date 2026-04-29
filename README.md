# 🌸 Flower Image Classification (CNN)

## Overview
This project builds a Convolutional Neural Network (CNN) to classify images of flowers into five categories:

- Daisy  
- Dandelion  
- Rose  
- Sunflower  
- Tulip  

The goal is to explore deep learning techniques for image classification and understand how CNNs learn visual features.

---

## Learning Objectives
- Understand how Convolutional Neural Networks (CNNs) work  
- Learn image preprocessing and dataset handling  
- Train and evaluate a deep learning model  
- Identify and address overfitting  

---

## Project Structure
```bash
flower-classification/
│
├── data/              # dataset (stored locally, not on GitHub)
├── notebooks/         # Jupyter notebooks
├── src/               # scripts (training, utilities)
├── requirements.txt
└── README.md
```

---

## Results & Observations

The model achieved high training accuracy (~96%) but significantly lower validation accuracy (~61%), indicating overfitting.

This suggests that the model learned patterns specific to the training data but struggled to generalise to unseen images.

Future improvements include:
- applying data augmentation
- adding dropout layers
- reducing model complexity
