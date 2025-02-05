# Facial Emotion Classification using Machine Learning and Deep Learning

This project investigates various machine learning and deep learning techniques for facial emotion classification, using a subset of the FER2013 image dataset. The notebook provides a comprehensive approach to feature extraction and classification of image data, starting with traditional machine learning methods and progressing to advanced deep learning techniques utilizing Keras. The dataset is available on Kaggle.

## Project Structure:

### 1. Library and Data Import

### 2. Data Preprocessing and Feature Descriptor Extraction for Conventional ML
- Image Sharpening
- Image Augmentation
- Histogram of Oriented Gradients
- Harris Corner Detectors
- Local Binary Patterns
- Canny Edge Detector
- Gray-Level Co-Occurrence Matrix

### 3. Conventional Machine Learning Approaches
- Support Vector Machine
- Ensemble Methods
- Gradient Boosting
- Stacking Approaches

### 4. Feature Selection based on SHAP

### 5. Deep Learning Approaches
- Transfer Learning

### 6. Error Analysis

### 7. Regularization Approaches
- Test Time Augmentation & Monte Carlo Dropout

## Key Findings:

### Best Deep Learning Approach:
- Achieved a test accuracy of **72.36%** by leveraging transfer learning, regularization, training and test-time augmentation, and Monte Carlo Dropout.

### Comparative Analysis:
- Deep learning models outperformed conventional machine learning methods by **18.6%** in terms of accuracy.

### Challenges:
- Facial emotion recognition (FER) remains a difficult task due to issues like emotion ambiguity, inconsistent labeling, and image quality.

## Potential Improvements:
- **Hyperparameter Tuning**: Further optimization of deep learning model hyperparameters could lead to better results.
- **Model Architecture Optimization**: Experimenting with different neural network architectures to determine the most effective structure for this task.
- **Ensemble Methods for Deep Learning**: Combining predictions from various Convolutional Neural Networks may improve performance even further.
