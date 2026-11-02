# Image Classification using ANN and CNN on the CIFAR-10 Dataset

## Project Overview

This project implements and evaluates Artificial Neural Network (ANN) and Convolutional Neural Network (CNN) models for image classification using the CIFAR-10 dataset.

The project explores how different neural network architectures can classify colour images into ten categories.

## Objectives

- Implement an ANN model using TensorFlow and Keras.
- Implement a CNN model for image classification.
- Preprocess and normalize image data.
- Train and evaluate both models.
- Compare their classification performance.

## Dataset

The CIFAR-10 dataset contains 60,000 colour images belonging to ten classes:

- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

Each image has dimensions of 32 × 32 pixels with three RGB colour channels.

The dataset consists of 50,000 training images and 10,000 testing images.

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook / Google Colab

## Methodology

1. Load the CIFAR-10 dataset.
2. Normalize the image pixel values.
3. Build the ANN architecture using fully connected layers.
4. Build the CNN architecture using convolutional, pooling, and fully connected layers.
5. Train both models on the training dataset.
6. Evaluate the models on the testing dataset.
7. Generate predictions for individual images.

## Project Structure

```text
CIFAR10-Image-Classification/
├── CIFAR10_ANN_CNN_Classification.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

## How to Run

1. Open the notebook using Google Colab or Jupyter Notebook.
2. Install the required Python libraries.
3. Run the notebook cells in order.
4. Train the ANN and CNN models.
5. Evaluate the models and inspect their predictions.

The CIFAR-10 dataset can be loaded using TensorFlow/Keras.

## Results and Performance Analysis

The ANN and CNN models were trained and evaluated using the CIFAR-10 dataset. Their performance was assessed using test loss and test accuracy.

### Model Performance Comparison

| Evaluation Metric | ANN Model | CNN Model |
|---|---|---|
| Training Epochs | 10 | 10 |
| Test Loss | Add actual result | Add actual result |
| Test Accuracy | Add actual result | Add actual result |
| Architecture | Fully Connected Layers | Convolutional and Fully Connected Layers |

### Observations

- **ANN:** The model uses fully connected layers to classify images based on their pixel values.
- **CNN:** The model uses convolutional layers to learn spatial features from images.
- **Performance Comparison:** Comparing test accuracy and test loss helps evaluate how effectively each architecture classifies unseen images.
- **Expected Outcome:** CNNs are generally better suited to image classification because they learn spatial patterns. However, the actual performance depends on the model architecture and training process.

### Conclusion

This experiment demonstrates the implementation and evaluation of ANN and CNN models for multiclass image classification. Comparing their test performance helps illustrate the advantages and limitations of each architecture when working with image data.


## Author

Eleti Sanjana
