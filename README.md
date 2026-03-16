# Chest X-ray Pneumonia Detection using CNN
This project implements a convolutional neural network (CNN) model to detect pneumonia from chest X-ray images.

## Dataset
The dataset used in this project is the **Chest X-Ray Pneumonia Dataset**, which contains labeled chest X-ray images for two classes:
- NORMAL
- PNEUMONIA
The dataset is widely used for medical image classification research.

## Methods
The pipeline of this project includes:
1. Loading chest X-ray images
2. Image preprocessing and normalization
3. Building a CNN model using TensorFlow/Keras
4. Training the model on the training dataset
5. Evaluating the model performance on validation and test datasets

The CNN architecture includes:
- Convolutional layers
- Max pooling layers
- Fully connected layers
- Sigmoid output layer for binary classification

## Results
- The model was trained for 5 epochs.
- Training accuracy reached approximately **97%**, and validation accuracy reached approximately **93%**.
- Test accuracy was approximately **74%**, which is reasonable for this dataset due to class imbalance and dataset variability.

## Tools and Libraries
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib

## Author
Biomedical Engineering Graduate Student  
Interested in medical AI and medical device applications
