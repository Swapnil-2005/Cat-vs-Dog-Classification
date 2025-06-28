# Cat-vs-Dog-Classification
🐱🐶 A CNN-based binary image classifier built using TensorFlow to distinguish between cats and dogs. Achieves ~80.58% validation accuracy on the Kaggle Dogs vs Cats dataset. Includes training plots, confusion matrix, and prediction support for custom images.
🐱🐶 Cat vs Dog Image Classifier using CNN
This project is a binary image classification model built using TensorFlow and Keras to distinguish between cats and dogs. It uses a custom Convolutional Neural Network (CNN) trained on the Kaggle Dogs vs Cats dataset. The model achieves around 80.58% validation accuracy and handles overfitting using batch normalization, dropout, and early stopping techniques.

✅ Features:
Built with a custom CNN architecture (3 Conv layers + FC layers)

Handles image preprocessing and normalization

Implements early stopping to prevent overfitting

Includes training history plots and confusion matrix visualization

Uses sklearn for metrics like accuracy, classification report, and confusion matrix

📊 Performance:
Validation Accuracy: ~80.58%

Balanced performance on both cat and dog classes

Visual tools for analyzing model performance
