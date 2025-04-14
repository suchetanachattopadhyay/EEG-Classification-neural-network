# EEG Seizure Classification using CWT and CNN

This repository contains the implementation of a deep learning pipeline for classifying EEG signals into three categories: **Normal**, **Pre-seizure**, and **Seizure**, using Continuous Wavelet Transform (CWT) and Convolutional Neural Networks (CNN). This work supports a research paper focused on EEG-based seizure detection using time-frequency representations and deep learning.

## Overview

- Raw EEG signals from the **Bonn University Dataset** are preprocessed.
- Continuous Wavelet Transform (CWT) is applied to convert EEG signals into 2D scalogram images.
- A custom CNN model is trained to classify the scalograms into 3 classes.
- Class balancing, class weights, and early stopping are implemented to improve model performance.
