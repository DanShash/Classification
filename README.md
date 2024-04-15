# MNIST Digit Classification Project

This project explores various aspects of machine learning classification using the MNIST dataset, which consists of 28x28 pixel images of handwritten digits (0-9). The goal is to build and evaluate machine learning models to accurately classify these digits.

## Project Overview

- **Data Exploration:** The project begins with an exploration of the MNIST dataset to understand its structure and features.
  
- **Binary Classification:** A binary classifier is trained to detect the digit "5" from the rest of the digits using the SGDClassifier. Evaluation metrics such as cross-validation, confusion matrices, precision, recall, and F1 scores are used to assess the model's performance.

- **Precision/Recall Trade-Off:** The project explores the precision/recall trade-off by adjusting the decision threshold of the classifier.

- **Multiclass Classification:** A multiclass classifier is trained using the SGDClassifier to classify all digits (0-9). The model's performance is evaluated using various metrics.

- **Error Analysis:** Error analysis is conducted to understand where the classifier is making mistakes, visualizing confusion matrices, and examining error instances.

- **Multilabel Classification:** A multilabel classification approach is implemented to predict two labels for each digit: whether it is large (7, 8, 9) and whether it is odd.

- **Multioutput Classification:** Multioutput classification is used to clean up noisy images by adding random noise to the dataset.

- **Hyperparameter Tuning:** GridSearchCV is utilized to tune hyperparameters for a KNeighborsClassifier, improving its accuracy.

- **Data Augmentation:** The MNIST dataset is augmented by shifting images, further improving the KNeighborsClassifier's accuracy.

## Results

With data augmentation, the project achieved an impressive accuracy rate on the MNIST dataset, demonstrating a solid understanding of classification concepts and various machine learning techniques.

## Usage

To run the project, ensure you have the necessary Python libraries installed. You can then execute the provided Jupyter notebook to reproduce the analysis and results.

---
