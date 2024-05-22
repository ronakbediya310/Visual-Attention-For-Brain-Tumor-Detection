# Brain Tumor Detection using Attention Mechanism in CNN

This project implements a Convolutional Neural Network (CNN) with attention mechanisms for brain tumor detection using MRI images. The code utilizes PyTorch for building and training the neural network.

## Project Overview:

The goal of this project is to classify MRI images into two categories: `yes` (tumor) and `no` (no tumor). The neural network model used is a CNN with attention mechanisms to enhance the feature extraction process.

## Dataset:

The dataset used in this project contains MRI images categorized into two classes: `yes` and `no`. The dataset is organized in a directory structure as follows:
![image](https://github.com/ronakbediya310/Visual-Attention-For-Brain-Tumor-Detection/assets/124416368/f4f99a18-b6f3-4491-8e36-ce2f3258d651)



## Model Architecture:

The model architecture consists of convolutional layers followed by attention blocks. The attention blocks help the model to focus on the relevant parts of the image, improving the classification performance.

## Requirements:

To run the code, you need to have the following installed:

- Python 3.x
- PyTorch
- torchvision
- scikit-learn
- PIL (Pillow)

You can install the required packages using the following command:
pip install torch torchvision scikit-learn pillow

## Attention Block:
The attention block is implemented to enhance the feature extraction process by focusing on the relevant parts of the image.
The model is trained using the **Adam optimizer and cross-entropy loss**.

## Results:
After training the model, the test accuracy will be printed. You can expect an accuracy around the reported value depending on the dataset and hyperparameters.

Test Accuracy: **0.9500**


