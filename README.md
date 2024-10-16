# Numerical Methods - Assignment 2

**Author:** Dascălu Ștefan-Nicolae, Group 321CA  
**Date:** May 6, 2023  

## Overview
This assignment explores various numerical methods, particularly focusing on image compression techniques and digit recognition using mathematical transformations.

## Key Concepts

1. **Singular Value Decomposition (SVD)**:
   - SVD is a method for decomposing a matrix into three other matrices, which helps in simplifying complex datasets and reducing dimensionality.
   - Used for image compression by retaining significant singular values while discarding the less important ones.

2. **Image Compression Using SVD**:
   - Developed a function that utilizes SVD to compress images, retaining most of the essential information while reducing the memory footprint.

3. **Principal Component Analysis (PCA)**:
   - PCA is a technique used to emphasize variation and bring out strong patterns in a dataset.
   - It reduces the dimensionality of large datasets while preserving as much variance as possible, making it useful for image compression.

4. **Digit Recognition**:
   - Implemented algorithms to recognize handwritten digits using PCA and the k-nearest neighbors (KNN) approach.
   - Utilized the MNIST dataset to train the model, achieving a recognition accuracy of approximately 93.3%.

5. **Function Implementation**:
   - Functions such as `task1` for SVD-based compression and `task2` for PCA-based compression were implemented to process images effectively.
   - The assignment also involved preparing the dataset, visualizing images, and applying KNN for classification.

## Conclusion
The assignment successfully demonstrated the application of numerical methods in image processing, showcasing techniques for efficient data compression and classification tasks.
