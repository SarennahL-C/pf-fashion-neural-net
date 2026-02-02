# Fashion MNIST — Neural Network Classification with PyTorch

This project implements a **Multilayer Perceptron (MLP) neural network** using PyTorch to classify images from the **Fashion MNIST dataset**. The task forms part of a structured machine learning assignment focused on building, training, and evaluating a neural network for multi-class image classification.

This project represents my **first modern neural network implementation**, providing hands-on experience with contemporary deep learning frameworks, training workflows, and model evaluation techniques.

![Table with 10 rows and 20 examples in each row. Each row is labelled eg "1 trouser" and then there are 20 examples of images in the MNIST dataset that have been classified as trousers. The images are all greyscale and the same square size.](Fashion-MNIST-Dataset-Images-with-Labels-and-Description-II-LITERATURE-REVIEW-In-image.png)

Figure reproduced from K V, Greeshma & Gripsy, Viji. (2020). Image Classification using HOG and LBP Feature Descriptors with SVM and CNN. via ResearchGate.

---

### What’s in this repository

- **Jupyter Notebook:** full neural network implementation (`fashion_mnist_task.ipynb`)  
- **Images:** visuals  
- **Requirements:** Python dependencies (`requirements.txt`)  

---

### Project Context

The Fashion MNIST dataset consists of 28×28 grayscale images representing ten categories of clothing and accessories, including items such as T-shirts, coats, sandals, sneakers, and bags.

The objective of the task was to:

- Build a neural network classifier using PyTorch  
- Train the model to achieve at least **80% accuracy** on the test dataset  
- Tune at least one hyperparameter and justify its selection  
- Evaluate model performance using accuracy, precision, recall, and F1-score  
- Interpret model behaviour using a confusion matrix  

The project provided a structured framework while requiring independent reasoning around model configuration, optimisation, and evaluation.

---

### Approach Overview

- Data loading and preprocessing using PyTorch datasets and transforms  
- Train–test splitting via DataLoader  
- Construction of a Multilayer Perceptron (MLP) architecture  
- Selection of activation functions and loss function  
- Model training using gradient descent optimisation  
- Hyperparameter tuning to improve classification performance  
- Evaluation using classification metrics and confusion matrix analysis  

---

### Key Insights / Findings

- Model performance improved through targeted hyperparameter tuning, demonstrating the sensitivity of neural networks to configuration choices.  
- Certain clothing classes exhibited stronger confusion due to visual similarity, particularly among upper-body garments.  
- Evaluation using macro-averaged metrics provided a more balanced view of performance across all classes.  
- The confusion matrix offered valuable insight beyond overall accuracy, highlighting where misclassifications occurred.  

---

### Personal Context

Although this was my first opportunity to **implement a modern neural network using PyTorch**, neural networks are not entirely new to my academic background.

My MPhil thesis (2001) involved the use of a neural network model to predict **stress relaxation behaviour in magnesium screws within a car engine environment**. While I did not develop the network code myself at that time — it was implemented by another member of the research group — I worked directly with the model as a predictive tool and interpreted its outputs within a materials science context. This gave me a deep understanding of the principles underlying neural networks and an appreciation of the strengths, potential pitfalls, and limitations of the method.

This project represents a meaningful bridge between **early exposure to neural network modelling** and contemporary hands-on implementation using modern deep learning frameworks. 

---

### Skills Demonstrated

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
- PyTorch  
- torchvision  
- scikit-learn  
- Python  
- Jupyter Notebook  

---

### Requirements

Install the required Python packages with: `pip install -r requirements.txt`

---

### Why this project belongs in my portfolio

This project demonstrates my ability to move from traditional machine learning techniques into modern deep learning workflows. It highlights both technical implementation and thoughtful evaluation, while also reflecting continuity in my long-standing interest in predictive modelling.

Together with my supervised and unsupervised learning projects, it represents an important step in my progression toward applied machine learning and neural network-based approaches.

