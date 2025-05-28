#About my project on GitHub
Multi-Modal Features Representation-Based 
Convolutional Neural Network Model for 
Malicious Website Detection


This repository contains the implementation of a Hybrid Convolutional Neural Network (HF-CNN) model designed to detect malicious websites by leveraging both textual and image-based URL representations. The project addresses the shortcomings of traditional blacklist and lexical-only methods by introducing a multi-modal deep learning approach for robust classification.


Multi-Modal Feature Extraction: Combines character-level n-gram textual features with image representations of URLs.

Dual CNN Models:

txtCNN: A 1D CNN trained on tokenized and padded URL text data.

imgCNN: A 2D CNN trained on grayscale image representations generated from TF-IDF feature matrices.

HF-CNN Decision Model: Fuses the outputs of both CNNs into a final classification layer to distinguish between benign and malicious URLs.
