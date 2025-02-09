# Fetal-Head-Abnormalities-Classification-using-ResNet50-and-MobileNetV3-Small
This project aims to analyze and compare the performance of state-of-the-art deep learning models in classifying fetal head abnormalities using the Fetal Head Abnormalities Dataset available on Kaggle. The primary focus is on implementing ResNet50 and MobileNetV3-Small.

## Problem Statement
Medical imaging plays a crucial role in prenatal healthcare by detecting abnormalities at an early stage, which can lead to timely interventions. The classification of fetal head abnormalities using deep learning can assist radiologists and clinicians in automating the screening process, reducing manual workload, and improving diagnostic accuracy.\
In this assignment, we aim to develop and compare two widely used convolutional neural networks (**ResNet50** and **MobileNetV3-Small**) for the classification of fetal head abnormalities. We explore the impact of different **augmentation techniques** and incorporate **Few-Shot Learning** to assess how well the models perform with limited labeled data.\
## Objectives
**1.Implement and train:**\
• **ResNet50:** A deep residual network architecture known for its strong feature extraction capabilities.\
![image](https://github.com/user-attachments/assets/cda0c2f5-f4ae-468e-b082-fc3bf747e833)\
• **MobileNetV3-Small:** A lightweight and efficient model optimized for mobile and edge devices.\
![image](https://github.com/user-attachments/assets/32a701b9-3972-4e38-9b3a-feccc62d0826)\
**2.Perform model training using:**\
• **Zero-Shot Learning (ZSL)** techniques: The ability of models to generalize without explicitly being trained on unseen abnormalities.\
• **Few-Shot Learning** (FSL): Training models with very few labeled examples per class.\
**3.Investigate the effect of different **data augmentation strategies**:**\
**Traditional augmentations:**\
 - Rotation\
 - Horizontal Flip\
 - Cropping\
## Advanced augmentations:
**Mixup:** A data augmentation technique that blends two images and their labels to improve generalization.\
![image](https://github.com/user-attachments/assets/d4b446d3-403b-49be-85e4-8195929f9a15)\
**CutMix:** Replaces a portion of an image with a patch from another image, encouraging stronger regularization.\
![image](https://github.com/user-attachments/assets/941975b8-e0e2-4e4c-9e58-1907cd83788c)\
**4.Evaluate performance using standard classification metrics:**\
  -- Confusion Matrix\
  -- Accuracy\
  -- Precision\
  -- Recall\
  -- F1-Score\\
**5.Compare and analyze** the results obtained from the two models.
## Dataset Details :\
The dataset used in this project is the **Fetal Head Abnormalities Dataset**, which consists of ultrasound images categorized into different classes of abnormalities. Proper preprocessing is required before training the models.\
### Key challenges of the dataset:\
•**Class Imbalance:** Some fetal head abnormalities might have significantly fewer samples than others.\
•**High Intra-Class Variability:** Variations in image quality, angles, and noise.\
•**Small Sample Size:** Few-Shot Learning techniques must be leveraged to improve generalization.
