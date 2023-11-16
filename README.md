# Automatic Object detection using Thermal imaging

## Overview

This Guava Disease Detection project implements a multi-model strategy to identify and classify diseases in guava leaves and fruits. Each model contributes uniquely to the detection process, enhancing accuracy and specificity.

#### Thermal Object Detection with YOLO v8

Utilizing YOLO v8, the project achieves robust thermal object detection with an mAP (mean Average Precision) of 67% and recall of 96.9%. The model excels in identifying guava fruits in thermal images, laying the foundation for subsequent disease classification.

#### Guava Fruit Classification with DenseNet121

Fine-tuning DenseNet121 results in a guava fruit disease classification model boasting an accuracy of around 92.3%. Leveraging the efficiency of DenseNet's feature extraction, the model accurately identifies and categorizes diseases affecting guava fruits.

#### Guava Fruit Classification with Machine Learning Models

- **Logistic Regression**: A logistic regression model provides an accuracy of 88% and a precision of 91%. This model contributes to disease classification in guava fruits, showcasing robust performance in identifying and categorizing specific diseases.

- **Support Vector Machine (SVM)**: The SVM model achieves an accuracy of 88% along with a precision of 91%. It significantly aids in disease classification, offering reliable identification and classification of diseases in guava fruits.


#### Guava Fruit Classification using Custom CNN Model

The custom CNN model for guava leaf disease classification achieves an accuracy of approximately 92%. Trained on a dataset specific to guava leaves, this model excels in recognizing and classifying various diseases affecting guava foliage.

#### Guava Leaf Disease Classification using Custom CNN Model

The custom CNN model for guava leaf disease classification achieves an outstanding test accuracy of 98%. Trained on a dataset specific to guava leaves, this model excels in recognizing and classifying various diseases affecting guava foliage.

#### Guava Fruit Disease Classification using Custom CNN Model

For guava fruit disease classification, two models are employed:

- **DenseNet121**: Achieving an accuracy of 90%, this model contributes significantly to the accurate identification and categorization of diseases affecting guava fruits.

- **Custom CNN Model**: With a commendable accuracy of 80%, the custom CNN model enhances the overall disease detection capabilities, offering an additional layer of classification for guava fruit diseases.



## Table of Contents
1. [Introduction](#introduction)
2. [Installation](#installation)
3. [Folder Structure](#folder-structure)
4. [Dataset](#dataset)
5. [Results](#results)

## Introduction


## Installation
To set up the project, follow these steps:
### 1. Clone the git repository
```bash
git clone https://github.com/JaswanthKrishnaE/Automatic-Object-detection-using-Thermal-imaging.git
```
### 2. Create a Virtual Environment
```bash
# open your project directory and Create a virtual environment
python -m venv venv
```
### 3. Activate the virtual environment
```bash 
# On Windows
venv\Scripts\activate
```
```bash
# On macOS/Linux
source venv/bin/activate
```
### 3. Install dependencies from requirements.txt
```bash
pip install -r requirements.txt
```

## Folder Structure

Below is the folder structure for the "Automatic-Object-detection-using-Thermal-imaging" project:

- `/Models`: This directory contains the trained models used for automatic object detection. Models are stored in serialized formats for easy distribution.

- `/NOTEBOOKS`: This directory includes Jupyter notebooks used for development, experimentation, or analysis. Users can explore and run these notebooks for a more in-depth understanding of the project.

- `/presentation`: This directory holds any presentation materials related to the project, such as slides, images, or documents used for showcasing the work.

- `/Reference papers`: This directory is dedicated to storing reference papers or documents that provide background information or inspiration for the project.

- `/Results`: The results of each model, including output files, logs, or relevant information generated during evaluation or testing, can be found in this directory.

- `Models.zip`: This compressed file contains all the trained models, providing a convenient way to download and deploy them for various applications.

- `myenv`: This directory may contain information related to the project's virtual environment, such as dependencies or configurations.

- `NOTEBOOKS`: This directory may hold additional notebooks or code snippets relevant to the project.

- `README.md`: The main documentation file that provides an overview of the project, instructions for installation and usage, and details about the dataset and results.

- `requirements.txt`: This file lists the Python packages and dependencies required to run the project. Users can use this file to set up the project environment.


## Dataset
### Guava Thermal Dataset :
The Guava Thermal Dataset provides thermal images of guava fruits, offering valuable insights for object detection or analysis based on thermal signatures. You can access this dataset on Roboflow [here](https://app.roboflow.com/indian-institute-of-information-technology-sricity/guava-h98xp/6).

### Guava Fruit Disease Dataset : 
The Guava Fruit Disease Dataset consists of images capturing various diseases affecting guava fruits. This dataset is available on Kaggle [here](https://www.kaggle.com/datasets/jaswanthkrishnaeaga/guava-disease-dataset/data).

### Guava Leaf Disease Dataset :
For guava leaf diseases, the Guava Leaf Disease Dataset contains images of leaves affected by different diseases. You can find this dataset on Kaggle [here](https://www.kaggle.com/datasets/omkarmanohardalvi/guava-disease-dataset-4-types).

## Results

The results of each model can be found in the `/Results` directory. This directory contains detailed output files, logs, or any relevant information generated during the evaluation or testing of the models. Users can explore this directory to analyze the performance and outcomes of the implemented models.
