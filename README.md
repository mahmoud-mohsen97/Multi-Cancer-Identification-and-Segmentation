# Problem Statement
This project aims to identify and segment different types of cancer diseases in brain and breast scans using deep learning techniques such as image classification and segmentation. The project uses a dataset containing images of brain cancer, tumor, no tumor, benign, malignant, and normal breast cancer.

# Project Objectives
- Apply different Image preprocessing techniques
- Apply Image Classification to classify each image as a brain or breast scan and determine if the scan is normal or infected with a tumor
- Apply Image segmentation to locate the infected area and measure the tumor's width and height, if present
- Generate a report that describes the data preparation process, the models used for classification and segmentation, the training and testing times for each model, and the obtained results for classification and segmentation using different metrics such as accuracy, precision, recall, dice coefficient, and IOU.
- Include screenshots of the segmentation results on the test images in the report.
# Dataset
The dataset used in this project can be found [here](https://drive.google.com/file/d/1VRG99lvzfhdC-YA5dfdj_a9IyMCl5WHH/view). The dataset contains the following folders/files:

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

