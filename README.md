# Animal Classification using InceptionV3

This project implements an animal classification model using the InceptionV3 deep learning architecture. The goal of this project is to accurately classify images of animals into their respective categories by leveraging the powerful feature extraction capabilities of InceptionV3.

## Project Overview

### 1. **Dataset**
   The dataset used in this project consists of images of various animal species. Each image is labeled with the corresponding animal category. The dataset was split into training, validation, and test sets to train and evaluate the model's performance.

### 2. **Model Architecture**
   The model is based on the InceptionV3 architecture, which is known for its efficiency and accuracy in image classification tasks. The model was pre-trained on the ImageNet dataset and fine-tuned on the animal dataset to adapt to the specific classification task.

### 3. **Training Process**
   - **Loss Function:** Categorical Cross-Entropy was used as the loss function, which is suitable for multi-class classification problems.
   - **Optimizer:** The Adam optimizer was employed to minimize the loss function, with an initial learning rate set to 0.001.
   - **Data Augmentation:** Techniques such as rotation, zoom, and horizontal flipping were applied to increase the diversity of the training data and prevent overfitting.

### 4. **Evaluation Metrics**
   - **Accuracy:** The main metric used to evaluate the model's performance. Both training and testing accuracies were tracked across epochs.
   - **Confusion Matrix:** A confusion matrix was generated to better understand the model’s performance on each animal category.

## Model Accuracy

The plot below illustrates the accuracy of the model on both the training and testing datasets over five epochs:

![Model Accuracy](Accuracy%20Results.png)

- The training accuracy shows a steady increase, indicating that the model is learning effectively from the training data.
- The testing accuracy remains consistently high, suggesting that the model generalizes well to unseen data.
