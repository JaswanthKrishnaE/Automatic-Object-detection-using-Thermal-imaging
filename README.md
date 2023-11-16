# Automatic Object detection using Thermal imaging

## Overview

## Table of Contents
1. [Introduction](#introduction)
2. [Installation](#installation)
3. [Folder Structure](#folder-structure)
4. [Dataset](#dataset)
5. [Results](#results)
6. [Trained Models](#results)

## Introduction


## Installation
To set up the project, follow these steps:
### 1. Clone the git repository
```bash
[git clone https://github.com/JaswanthKrishnaE/Automatic-Object-detection-using-Thermal-imaging.git
cd Automatic-Object-detection-using-Thermal-imaging](https://github.com/JaswanthKrishnaE/Automatic-Object-detection-using-Thermal-imaging.git)
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

## Trained Models

All trained models are conveniently compressed and zipped into the `models.zip` file. This archive contains the serialized versions of the models, allowing users to easily download and deploy them for various applications. The compressed file provides a compact and organized way to distribute or share the trained models without the need to transfer individual files.

To use the trained models, follow these steps:

1. **Extract the Models:**
    ```bash
    unzip models.zip
    ```
2. **Integrate the Models:**
    Use the extracted model files in your applications or projects for inference or further training.
