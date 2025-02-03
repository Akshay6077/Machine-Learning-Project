# Multi-Modal Image Classification System

## Overview
A comparative analysis project implementing three distinct machine learning approaches (CNN, SVM, and KNN) for image classification, featuring comprehensive hyperparameter optimization and performance evaluation.

## Key Features
- Implemented GridSearchCV for optimal hyperparameter selection
- Designed custom CNN architecture with dropout regularization
- Integrated SVM with RBF kernel optimization
- Enhanced KNN with Manhattan distance metrics
- Generated detailed performance metrics and visualizations

## Technical Details

### Model Architectures
- **CNN**: Custom architecture with dropout layers
- **SVM**: RBF kernel (C=10, gamma='scale')
- **KNN**: Manhattan distance metric, k=3, weighted voting

### Performance Results
- SVM: 86.3% accuracy
- CNN: 83.7% accuracy
- KNN: 83.2% accuracy

## Technologies Used
- Python
- TensorFlow/Keras
- Scikit-learn
- NumPy
- Pandas
- Matplotlib/Seaborn

## Implementation Highlights
- Complete ML pipeline in single Jupyter notebook
- Modular code structure for easy adaptation
- Interactive hyperparameter exploration
- Visual performance comparisons

