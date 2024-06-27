# Face Mask Detection using CNN

## Overview

This project focuses on developing a Convolutional Neural Network (CNN) model to detect whether a person is wearing a face mask. The model is built using TensorFlow and Keras, and is trained on a dataset consisting of images of people with and without masks. The project aims to achieve high accuracy in real-time face mask detection.

## Dataset

The dataset used for this project is sourced from Kaggle and can be found [here](https://www.kaggle.com/datasets/omkargurav/face-mask-dataset). It consists of two categories:
- **With Mask**
- **Without Mask**

## Project Details

**Project Title**: Face Mask Detection using CNN  
**Duration**: February 2024  
**Author**: Salil Lokhande  
**Email**: [salillokhande14@gmail.com](mailto:salillokhande14@gmail.com)

## Key Features

- **CNN Model Development**: Utilized TensorFlow and Keras to develop a CNN model capable of real-time face mask detection.
- **Data Preprocessing**: Implemented rigorous image preprocessing and extensive data augmentation to enhance model robustness and generalization.
- **Model Performance**: Achieved a training accuracy of 92.61% and a test accuracy of 93.12%.

## Implementation

### Data Preprocessing

- Resized all images to 128x128 pixels.
- Converted images to RGB format.
- Normalized pixel values.

### Model Architecture

- **Convolutional Layers**: Applied Conv2D layers with ReLU activation.
- **Pooling Layers**: Used MaxPooling2D layers for downsampling.
- **Fully Connected Layers**: Included Dense layers with Dropout for regularization.
- **Output Layer**: Used a Dense layer with sigmoid activation to classify the images.

### Training

- **Optimizer**: Adam
- **Loss Function**: Sparse Categorical Crossentropy
- **Metrics**: Accuracy
- **Epochs**: 5
- **Validation Split**: 10%

### Evaluation

The model was evaluated on the test set, achieving an accuracy of 93.12%.

## Results

- **Training Accuracy**: 92.61%
- **Test Accuracy**: 93.12%

The model demonstrated high accuracy in detecting face masks in real-time.

## Visualization

- **Training and Validation Loss**: Plotted loss values over epochs.
- **Training and Validation Accuracy**: Plotted accuracy values over epochs.

## Conclusion

This project successfully developed a CNN model for real-time face mask detection, achieving high accuracy through effective image preprocessing, data augmentation, and model tuning.

---

Feel free to explore the [Face Mask Detection using CNN.ipynb](Face%20Mask%20Detection%20using%20CNN.ipynb) notebook for detailed implementation.

---

### Contact

For any questions or collaboration inquiries, please contact:

**Salil Lokhande**  
Email: [salillokhande14@gmail.com](mailto:salillokhande14@gmail.com)
