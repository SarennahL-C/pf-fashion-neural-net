# Fashion MNIST — Neural Network Classification with PyTorch

This project implements a **Multilayer Perceptron (MLP) neural network** using PyTorch to classify images from the **Fashion MNIST dataset**. The objective was to build, train, and evaluate a neural network for multi-class image classification, while developing familiarity with modern deep learning workflows and evaluation practices.

This project represents my **first hands-on implementation of a modern neural network**, providing practical experience with PyTorch, optimisation workflows, and performance assessment.

![Fashion MNIST sample images](Fashion-MNIST-Dataset-Images-with-Labels-and-Description-II-LITERATURE-REVIEW-In-image.png)

<sub>Figure reproduced from K. V. Greeshma & V. Gripsy (2020), via ResearchGate.</sub>

---

## What’s in this repository

- **Jupyter Notebook:** full neural network implementation (`fashion_mnist_task.ipynb`)  
- **Images:** visualisations and evaluation outputs  
- **Requirements:** Python dependencies (`requirements.txt`)  

---

## Project Context

The Fashion MNIST dataset consists of 28×28 grayscale images representing ten categories of clothing and accessories, including items such as T-shirts, coats, sandals, sneakers, and bags.

The task was to design and train a neural network classifier capable of achieving strong performance on unseen data, while also demonstrating appropriate evaluation and interpretation of results. Emphasis was placed on understanding model behaviour, tuning hyperparameters thoughtfully, and assessing performance across all classes rather than relying on accuracy alone.

---

## Approach Overview

The analysis followed a standard neural network workflow:

- Data loading and preprocessing using PyTorch datasets and transforms  
- Train–test splitting via DataLoader  
- Construction of a Multilayer Perceptron (MLP) architecture  
- Selection of activation functions and loss function  
- Model training using gradient-based optimisation  
- Targeted hyperparameter tuning  
- Evaluation using classification metrics and confusion matrix analysis  

---

## Key Insights / Findings

- Model performance improved through targeted hyperparameter tuning, demonstrating the sensitivity of neural networks to configuration choices.  
- Certain clothing categories exhibited higher confusion due to visual similarity, particularly among upper-body garments.  
- Macro-averaged precision, recall, and F1-score provided a more balanced view of model performance across all classes.  
- Confusion matrix analysis offered insight beyond overall accuracy, highlighting specific patterns of misclassification.  

---

## Skills Demonstrated

**Analysis**
- Data preprocessing for image classification  
- Interpretation of classification results  

**Modelling**
- Multilayer Perceptron (MLP) neural networks  
- Activation functions and loss functions  
- Hyperparameter tuning  

**Evaluation**
- Confusion matrix interpretation  
- Accuracy, precision, recall, and F1-score (macro average)  

**Tools**
- Python  
- PyTorch  
- torchvision  
- scikit-learn  
- Jupyter Notebook  

---

## Requirements

Install the required Python packages with: `pip install -r requirements.txt`

---

## Why this project belongs in my portfolio

This project demonstrates my transition from classical machine learning techniques into modern deep learning workflows, with a focus on implementation, evaluation, and interpretation rather than optimisation alone.

While this represents my first practical implementation of a neural network using PyTorch, it builds on earlier academic experience working with neural network models as analytical tools. Together with my other supervised, unsupervised, and deep learning projects, it marks an important step in my progression toward applied machine learning and neural network–based approaches.
