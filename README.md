# Face Mask Detection using CNN

This project implements a Convolutional Neural Network (CNN) to detect whether a person is wearing a face mask or not.

## Overview

The model identifies two classes:
1.  **With Mask**
2.  **Without Mask**

It uses a deep learning model trained on a dataset of images categorized into these two classes.

## Dataset

The dataset is located in the `data/` directory, containing:
-   `with_mask/`: Images of people wearing masks.
-   `without_mask/`: Images of people not wearing masks.

(Note: The data is currently zipped in `data/with_mask.zip` and `data/without_mask.zip`. You may need to unzip them to use).

## Requirements

To run this project, you need the following Python libraries:

-   tensorflow
-   numpy
-   matplotlib
-   opencv-python
-   scikit-learn
-   pillow

You can install them using:
```bash
pip install -r requirements.txt
```

## Usage

1.  Clone the repository.
2.  Install dependencies.
3.  Run the Jupyter Notebook `Face_Mask_Detection_using_CNN.ipynb`.
    -   If running locally, ensure you have the dataset extracted.
    -   The notebook guides you through data loading, preprocessing, model training, and evaluation.

## Model

The model is built using Keras (TensorFlow backend) with Convolutional layers (Conv2D), Max Pooling, and Dense layers to classify the images.
