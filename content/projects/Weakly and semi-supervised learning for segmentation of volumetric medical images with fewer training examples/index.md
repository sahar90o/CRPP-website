---
title: Weakly and semi-supervised learning for segmentation of volumetric medical images with fewer training examples
image: 
  focal_point: "top"
---


<!--more-->

**Background:** 

Advanced machine learning technologies have revolutionized image analysis in the recent years. In various vision tasks, current methods that utilize multi-layered neural networks, a.k.a. deep learning, reach near-human performance. Tasks related to medical image computing have also seen a surge in performance with the introduction of deep learning techniques. In particular, performance of DL-based algorithms in automatic segmentation and detection of normal structures and lesions have reached a level where these methods can accelerate clinical workflow in radiology and radiation oncology, and enable high-throughput imaging-based clinical research. One of the most important components that lead to DL’s recent success is the availability of large-scale labeled datasets. DL algorithms have large number of parameters that allow them to represent complex patterns of statistical dependence between explanatory and outcome variables. In segmentation of medical images, the labeled examples needed for training DL algorithms consists of images showing the structure of interest and corresponding pixel-wise annotations delineating the boundaries of the structure. The resource requirements for creating large labeled datasets create an obstacle for applying DL algorithms on new problems. 


**Working hypothesis:** 


1- DL-based segmentation methods can be trained using “weak” labels in the form of scribbles rather than detailed boundary delineations and this strategy would require less resource commitments in terms of number of expert-hours for creating datasets of training examples.

2- Very accurate DL-based medical image segmentation methods can be trained using few labeled and large number of “un-labeled” examples, where only the image is available.



**Specific aims for this research project:**

1- Develop novel algorithms to train DL-based segmentation methods for volumetric medical images using weak segmentation labels.

2- Develop novel semi-supervised / self-supervised volumetric segmentation methods that utilizes unlabeled images along with few labeled examples. This is illustrated in below figure.

3- Investigate application of the developed techniques for segmenting brain tumors in MRI (relation to WP2 and WP7), lymph nodes and stations in the head-and-neck area (relation to WP5).



