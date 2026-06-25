# Image Classification using CNNs 

This directory contains my hands-on implementation and notes for **Image Classification** using Convolutional Neural Networks (CNNs). It marks the transition from understanding basic spatial filters to building an end-to-end pipeline that can classify visual data.

---

##  Theoretical Foundations of Image Classification

Before diving into the code, I focused on how a computer actually interprets and processes an image classification task:

* **The Image Representation:** An image is essentially a matrix of pixel values (or three matrices for RGB color channels). Classification requires mapping these raw numerical grids to a specific discrete label.
* **Feature Extraction vs. Classification:** Traditional machine learning required hand-crafting features (like edges or color histograms). With CNNs, the network learns to extract these features automatically—starting with low-level edges in the early layers and building up to complex object parts in the deeper layers.
* **Softmax & Cross-Entropy:** For multi-class classification, the final layer uses a Softmax activation function to output a probability distribution across all classes, while Categorical Cross-Entropy loss is used to measure how far off the predictions are from the true labels during training.

---

##  My Pipeline Approach

To tackle the classification problem systematically, I followed a standard deep learning workflow:

1. **Data Preprocessing & Augmentation:** Loaded the dataset, normalized pixel values (scaling them between 0 and 1 for faster convergence), and applied transformations like resizing and shuffling.
2. **Model Architecture Design:** Designed a sequential CNN structure alternating between Convolutional layers (to extract spatial features) and Max Pooling layers (to reduce dimensionality), ending with Dense layers for the final classification.
3. **Compilation & Training:** Used efficient optimizers (like Adam) to update weights and tracked metrics like training/validation accuracy and loss over multiple epochs to monitor performance.

---

##  Interactive Notebook

You can view my complete code implementation, training loops, and accuracy curves directly in Google Colab:

*  **[Open my Image Classification Notebook in Colab](https://colab.research.google.com/drive/1Z3IA5qnJQjmKC-N2733UUTh3m39AeUgo#scrollTo=KxdRS0KJGTxX)**

---

##  Practice Files & Topics Covered

* **`practice img_classification`**: Contains the code runs, model setups, and experimental graphs.
* **`week 1 & 2 Topics covered`**: Core logs tracking the transition from theoretical deep learning concepts to building live image classification models.
