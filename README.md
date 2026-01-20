Pneumonia Detection from Chest X-Rays

This project features a deep learning model developed for the BioFusion hackathon (University of Sri Jayewardenepura, 2026) designed to assist in the early detection of pneumonia. The model is a custom CNN architecture that was built and trained entirely from scratch. It specifically avoids the use of pre-trained models to ensure that the convolutional kernels are optimized for the high-contrast, grayscale textures of lung radiographs rather than natural world objects.

Dataset: https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia

The custom Convolutional Neural Network architecture extracts hierarchical features through multiple convolutional layers, utilizes Batch Normalization and ReLU activation for stable non-linear operations, and incorporates Max Pooling and Dropout regularization to efficiently reduce dimensionality while preventing overfitting. 
