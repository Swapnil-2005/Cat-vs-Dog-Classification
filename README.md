# Cat-vs-Dog-Classification
🐱🐶 Cat-vs-Dog-Classification (91 % accuracy)

A CNN-based binary image classifier built using TensorFlow to distinguish between cats and dogs. The project explores different model architectures and techniques to improve classification accuracy on the Kaggle Dogs vs Cats dataset. It includes training plots, confusion matrices, and prediction support for custom images.

📌 Approaches & Accuracy:

✅ Transfer Learning: Achieved ~91.27% validation accuracy.

🛠 Custom CNN (Manual): Achieved ~80.58% validation accuracy.

🚫 Without Data Augmentation: Validation performance observed with basic preprocessing (lower accuracy).


✅ Features:

Built using both custom CNN architecture (3 Conv layers + FC layers) and transfer learning (e.g., VGG, ResNet).

Handles image preprocessing, normalization, and data augmentation.

Implements early stopping, batch normalization, and dropout to prevent overfitting.

Includes training history plots, confusion matrix, and performance visualization.

Uses sklearn for metrics like accuracy, classification report, and confusion matrix.

📊 Performance:

Best Validation Accuracy: ~91.27% (Transfer Learning)

Custom CNN Validation Accuracy: ~80.58%

Balanced classification across both cat and dog classes

📁 Notebooks Included:

1. cat_vs_dog_dataaugmentation.ipynb – Training with data augmentation using a custom CNN


2. cat_vs_dog_transferlearning.ipynb – Training using transfer learning (e.g., VGG, ResNet)


3. cat_vs_dog_w/o_dataaugmentation.ipynb – Training without data augmentation





Visual tools for analyzing model performance
kaggle dataset link:https://www.kaggle.com/datasets/salader/dogs-vs-cats
