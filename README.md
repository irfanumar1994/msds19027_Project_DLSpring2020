# msds19027_Project_DLSpring2020
This repository contains code and results for the Course Project by Deep Learning Spring 2020 course offered at Information Technology University, Lahore, Pakistan. This repository is only for learning purposes and is not intended to be used for commercial purposes.
Course website: http://im.itu.edu.pk/deep-learning-spring-2020/

# Dataset:
https://www.kaggle.com/c/prostate-cancer-grade-assessment/data

# Abstract:
The identification of prostate cancer is depending on the grading of prostate tissue biopsies. These tissues are examined based on Gleason score and ISUP score. Deep learning has achieved pathologist level results for the identification and grading of prostate cancer. However, there is a need to test deep learning models on the multi-center dataset that has not been done yet. For this study, Kaggle provides a multi-center dataset with nearly 11,000 images of prostate biopsy labelled by based on Gleason scoring and ISUP grades in PANDA challenge. We employed convolutional neural networks VGG16, ResNet18 to classify these prostate biopsies. ResNet18 has given 99% training accuracy and 78% validation accuracy on the processed tiled images of prostate biopsy. While we have also utilized image masks as ground truth for semantic segmentation on patches of biopsies and their masked ground truth. Due to GPU limitations, we were unable to run UNet on full data, but for 1000 images we over fitted the model.

# Results:

![GitHub Logo](https://github.com/irfanumar1994/msds19027_Project_DLSpring2020/blob/master/results_.JPG)

# Model Weights:
https://drive.google.com/drive/folders/1I4IciZSW8zKnqM6mK6wpCufQg45LKQTZ?usp=sharing
