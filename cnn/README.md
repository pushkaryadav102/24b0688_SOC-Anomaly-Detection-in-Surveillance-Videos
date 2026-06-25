# Convolutional Neural Networks (CNN) 

Welcome to the CNN module of the **Anomaly Detection in Surveillance Videos** project. This section documents my fundamental understanding, implementation approach, and practical exercises involving Convolutional Neural Networks.

---

##  What is a CNN?

A **Convolutional Neural Networks (CNN)** is a class of deep learning architectures primarily designed for processing structured grid data, such as images. Unlike traditional multi-layer perceptrons, CNNs leverage spatial hierarchies and local patterns through specialized layers, making them highly efficient for computer vision tasks.

### Key Components:
* **Convolutional Layer:** Applies filters (kernels) to the input to detect local features like edges, textures, and shapes.
* **Activation Function (ReLU):** Introduces non-linearity into the network, allowing it to learn complex patterns.
* **Pooling Layer (Max/Average Pooling):** Reduces the spatial dimensions (width x height) of the feature maps, decreasing computational load and helping extract dominant features.
* **Fully Connected (FC) Layer:** Flattens the extracted features and connects them to a standard neural network layer to perform final classification or regression.

---

##  My Approach to Understanding CNNs

To build a strong foundation for video anomaly detection, I approached CNNs through a structured, step-by-step learning curve:

1.  **Theoretical Foundation:** Studied the mathematical intuition behind matrix convolutions, pooling mechanisms, and backpropagation in spatial layers.
2.  **Architectural Evolution:** Reviewed classic CNN architectures (such as LeNet-5, AlexNet, and VGG) to understand how deep feature extraction has evolved over time.
3.  **Video Anomaly Context:** Analyzed how spatial features extracted by a CNN form the backbone for temporal analysis (like combining them with RNNs/LSTMs or using 3D-CNNs) to detect unusual activities in surveillance footage.

---

##  How I Practiced CNNs

To transition from theory to hands-on proficiency, I completed the following practical exercises and implementations:

* **Custom CNN Architectures:** Built and trained a standard CNN from scratch using frameworks like TensorFlow/Keras or PyTorch to classify foundational datasets (e.g., MNIST, CIFAR-10).
* **Hyperparameter Tuning:** Experimented with varying filter sizes, stride lengths, padding methods, and learning rates to observe their direct impact on model accuracy and loss curves.
* **Overfitting Mitigation:** Practiced implementing Regularization techniques, such as **Dropout layers** and **Data Augmentation** (rotation, flipping, zooming), to enhance model generalization.

## Colab Notebook of practiced CNN
*  **[Open my CNN Practice Notebook in Colab](https://colab.research.google.com/drive/1WSFYO2hk3FEFmGVX3QLs2-0ClJCWrXEX)**
