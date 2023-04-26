# Melanoma Classification using Custom CNN in TensorFlow assignment 

This project aims to build a custom convolutional neural network (CNN) model in TensorFlow to accurately classify skin images into one of nine oncological diseases, including melanoma. The model's performance could help dermatologists detect melanoma early and reduce the manual effort needed for diagnosis.

## Dataset

The dataset used in this project consists of 2357 images of malignant and benign oncological diseases, including melanoma, from the International Skin Imaging Collaboration (ISIC). The data set includes the following diseases: Actinic keratosis, Basal cell carcinoma, Dermatofibroma, Melanoma, Nevus, Pigmented benign keratosis, Seborrheic keratosis, Squamous cell carcinoma, and Vascular lesion. The data set is slightly imbalanced, with melanomas and moles having more images than other diseases.

## Project Pipeline

The project pipeline consists of the following steps:

1. Data Reading/Data Understanding → Defining the path for train and test images
2. Dataset Creation → Create train & validation dataset from the train directory with a batch size of 32. Also, resize your images to 180*180.
3. Dataset visualization → Create a code to visualize one instance of all the nine classes present in the dataset.
4. Model Building & training → Create a CNN model, choose an appropriate optimizer and loss function for model training, train the model for ~20 epochs, and write your findings after the model fit.
5. Data Augmentation Strategy → Choose an appropriate data augmentation strategy to resolve underfitting/overfitting.
6. Model Building & training on the augmented data → Create a CNN model on the augmented data, train the model for ~20 epochs, and write your findings after the model fit.
7. Class Distribution → Examine the current class distribution in the training dataset and determine which class has the least number of samples and which classes dominate the data in terms of the proportionate number of samples.
8. Handling Class Imbalances → Rectify class imbalances present in the training dataset with the Augmentor library.
9. Model Building & training on the rectified class imbalance data → Create a CNN model on the rectified class imbalance data, train the model for ~30 epochs, and write your findings after the model fit.

## Files

This repository contains the following files:

- `data/`: Directory containing the dataset
- `rudra.ipynb`: The main Jupyter Notebook for this project
- `README.md`: The README file for this project

## Instructions

To run the project, follow these steps:

1. Clone this repository.
2. Download the dataset from the link provided in the assignment.
3. Place the dataset in the `data/` directory.
4. Open `melanoma_classification.ipynb` in Jupyter Notebook.
5. Run each cell in the notebook in order.

## Conclusion

In this project, we built a custom CNN model to classify skin images into one of nine oncological diseases, including melanoma. We used data augmentation techniques and rectified class imbalances to improve the model's performance. We hope this project could be useful for dermatologists in detecting melanoma early and reducing manual effort needed for diagnosis.