# OpenCV Practice Report

 **[OpenCV Practice Colab Notebook](https://colab.research.google.com/drive/1xXEh34w7lYWw6pv0xyS5l_H7_WiZtSlu?usp=sharing)**

## 1. Introduction to OpenCV
OpenCV (Open Source Computer Vision Library) is an open-source computer vision and machine learning software library. It provides a common infrastructure for computer vision applications and accelerates the use of machine perception in commercial products. Written natively in C++, it has highly optimized interfaces for Python, Java, and MATLAB, making it the industry standard for real-time image and video processing.

---

## 2. Core Concepts & Operations Practiced
During this practice module, the following foundational computer vision techniques were explored and implemented:

* **Image I/O & Manipulation:** Loading (`cv2.imread`), displaying, and saving images, as well as understanding pixel manipulations and color space conversions (e.g., BGR to Grayscale, BGR to HSV).
* **Geometric Transformations:** Resizing, cropping, rotating, and translating images to alter their spatial orientations.
* **Image Filtering & Smoothing:** Applying blurring techniques (Gaussian, Median, and Bilinear filters) to reduce noise in visual data.
* **Edge & Feature Detection:** Utilizing gradients and algorithms like the Canny Edge Detector to isolate structural boundaries within images.
* **Thresholding & Binarization:** Implementing simple and adaptive thresholding to separate foreground objects from background environments.

---

## 3. Significance in Surveillance & Anomaly Detection
In the context of processing surveillance video feeds, OpenCV serves as the crucial preprocessing engine. By leveraging techniques like frame differencing, background subtraction, and contour detection, we can isolate moving objects, reduce background noise, and extract clean feature maps. These preprocessed frames directly feed into downstream deep learning architectures (like CNNs) to effectively detect anomalies or irregular behaviors in real-time.

---

## 4. Google Colab Practice Notebook
The complete hands-on code implementations, visual outputs, and experimental steps for these OpenCV operations are documented in the interactive notebook below:

👉 **[Access the OpenCV Practice Notebook]()**
