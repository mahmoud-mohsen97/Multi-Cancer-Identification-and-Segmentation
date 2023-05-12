# Problem Statement
This project aims to identify and segment different types of cancer diseases in brain and breast scans using deep learning techniques such as image classification and segmentation. The project uses a dataset containing images of brain cancer, tumor, no tumor, benign, malignant, and normal breast cancer.

# Project Objectives
- Apply different Image preprocessing techniques
- Apply Image Classification to classify each image as a brain or breast scan and determine if the scan is normal or infected with a tumor
- Apply Image segmentation to locate the infected area and measure the tumor's width and height, if present
- Generate a report that describes the data preparation process, the models used for classification and segmentation, the training and testing times for each model, and the obtained results for classification and segmentation using different metrics such as accuracy, precision, recall, dice coefficient, and IOU.
- Include screenshots of the segmentation results on the test images in the report.
# Dataset
The dataset used in this project can be found here. The dataset contains the following folders/files:

- Brain Cancer
  - Tumor
    - Train (Images that will be used for training the model)
    - Test (Images that will be used for testing the model)
    - Train_masks (Segmentation masks for the Train folder Images)
    - Test_masks (Segmentation masks for the Test folder Images)
  - No Tumor
    - Train (Images that will be used for training the model)
    - Test (Images that will be used for testing the model)
- Breast Cancer
  - Benign
    - Train (consists of the training images with their corresponding segmentation masks)
    - Test (consists of the testing images with their corresponding segmentation masks)
  - Malignant
    - Train (consists of the training images with their corresponding segmentation masks)
    - Test (consists of the testing images with their corresponding segmentation masks)
  - Normal
    - Train (consists of the training images)
    - Test (consists of the testing images)
# Getting Started
To get started, clone this repository and download the dataset from the link provided above. Then, follow the instructions in the report to run the code and reproduce the results.

# Requirements
- Python 3.6+
- TensorFlow 2.0+
- Keras 2.3+
- NumPy
- OpenCV
- Matplotlib
# Results
The results obtained from this project can be found in the report included in this repository. The report describes the data preparation process, the models used for classification and segmentation, the training and testing times for each model, and the obtained results for classification and segmentation using different evaluation metrics.

# Contribution
We welcome contributions to this project. If you have any suggestions or ideas, please feel free to open an issue or a pull request.

Thank you for your interest in our project!
