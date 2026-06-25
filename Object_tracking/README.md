# Object Tracking Practice Report

## 1. Introduction to Object Tracking
Object tracking is the process of locating a moving object (or multiple objects) over time using a camera feed. Unlike object detection, which identifies and locates objects in a single, isolated frame, tracking associates objects across continuous frames. It forms a critical component in video surveillance, traffic monitoring, and autonomous driving systems.

---

## 2. Core Concepts & Workflow Practiced
During this practice module, the following dataset management, object detection, and tracking methodologies were explored:

* **Dataset Integration with Roboflow:** Utilizing Roboflow to host, version, and preprocess annotated image datasets, allowing for streamlined integration of custom classes into the computer vision pipeline.
* **Tracking-by-Detection:** Leveraging initial deep learning object detection bounding boxes to predict and track target positions in successive frames.
* **Optical Flow (Lucas-Kanade & Farneback):** Analyzing the pattern of apparent motion of image intensities between consecutive frames to track specific pixels or dense feature maps.
* **Kernel-Based Tracking (MeanShift / CamShift):** Tracking objects by iteratively maximizing a similarity metric between a target color histogram model and candidate image regions.
* **Modern Multi-Object Tracking (MOT):** Understanding algorithms like SORT or DeepSORT, which combine bounding box overlap (IoU) and deep appearance features to maintain consistent identity tags on multiple moving targets.

---

## 3. Relevance to Surveillance & Anomaly Detection
In automated surveillance systems, tracking transforms raw spatial detections into meaningful behavior analysis. While an object detector pinpointing a target frame-by-frame is helpful, tracking charts their full trajectory. This continuous path mapping is vital for identifying behavioral anomalies, such as:
* Vehicles driving the wrong way down a lane.
* Loitering or trespassing in restricted perimeters.
* Sudden, erratic movements indicating accidents or security breaches.

---

## 4. Google Colab Practice Notebook
The complete hands-on code implementations, Roboflow integrations, and experimental outputs for these tracking techniques are documented in the interactive notebook below:

 **[Object Tracking Practice Colab Notebook](https://colab.research.google.com/drive/1jPurQETgy7aX9mbFopfMq9x4DBxqEV9E?usp=sharing)**
