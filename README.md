# BDAM-XBD
Building Damage Assessment Machine Learning Model utilizing XBD dataset and Random Forest algorithm, with ongoing development of a CNN model based on ResNet architecture.
## Building Damage Assessment Machine Learning Model

[![GitHub](https://img.shields.io/badge/GitHub-Repository-brightgreen)](https://github.com/mustafabukh/BDAM-XBD)
[![License](https://img.shields.io/badge/License-MIT-blue)](https://opensource.org/licenses/MIT)

This GitHub repository contains the implementation of a project that aims to locate damaged areas after an earthquake using satellite images, a Building Damage Assessment Machine Learning Model, developed as a part of a school project. The project focuses on utilizing the XBD dataset and employs the Random Forest algorithm for accurate prediction and assessment of building damages. Additionally, the project is being expanded to include a Convolutional Neural Network (CNN) model based on the ResNet architecture for further improvement in performance.

### Project Overview
The primary objective of this project is to develop a machine learning model that can automatically assess the damage levels of buildings based on provided data. The model utilizes the XBD dataset, which consists of labeled images and corresponding damage severity annotations. By training a Random Forest algorithm on this dataset, the model can predict the damage severity for unseen building images. Furthermore, the project is actively working on incorporating a CNN model based on the ResNet architecture to enhance the performance of the building damage assessment.

### Dataset
The XBD dataset is a publicly available dataset specifically designed for building damage assessment tasks. It contains a large collection of images depicting buildings, accompanied by corresponding damage labels indicating the severity of the damage. The dataset is carefully curated and labeled, ensuring its suitability for training and evaluating machine learning models.


### Repository Structure

**Note: For now, the project is contained within a single main notebook and will be restructured as the development progresses.**

The repository is structured as follows:

- `preprocessing/`: This directory contains scripts and notebooks for preprocessing the XBD dataset, including resizing images, normalizing pixel values, and encoding labels.

- `feature_extraction/`: This directory contains scripts and notebooks for extracting relevant features from the preprocessed images.

- `model_training/`: This directory contains scripts and notebooks for training the Random Forest model using the extracted features.

- `evaluation/`: This directory contains scripts and notebooks for evaluating the trained model and analyzing its performance using various metrics.

- `cnn_model/`: This directory, currently under development, will contain scripts and notebooks for implementing the CNN model based on the ResNet architecture.

- `README.md`: This file provides an overview of the project, instructions for setting up the environment, and usage guidelines.

### Usage

Download the xBD Dataset: In order to train and test the earthquake damage detection model, you need to download the xBD dataset. The dataset can be obtained from (https://xview2.org/). Download the dataset and extract the relevant files to a local directory on your machine.
Point URLs in the Code: Open the main.ipynb notebook and look for sections or cells where URLs need to be specified for accessing the downloaded xBD dataset files. Update these URLs to point to the corresponding files on your machine.

### Features to be Added (Future Work)

The project is currently focused on implementing the Random Forest classifier for earthquake damage detection. However, there are several features that can be added in the future to further enhance the capabilities of the project. These include:

1. **CNN Model Development**: As mentioned earlier, the project is actively working on developing a CNN model based on the ResNet architecture. Once completed, this model will be integrated into the project, providing an alternative approach to detecting and locating damaged areas after an earthquake.

2. **Semantic Segmentation**: In addition to classifying damaged and undamaged areas, semantic segmentation techniques can be incorporated to identify specific types of damage, such as collapsed structures, cracks, or structural instability. This can provide more detailed information for rescue and recovery efforts.

3. **Post-processing Techniques**: Post-processing techniques, such as morphological operations and contour analysis, can be applied to refine the detected damaged areas and remove any false positives or artifacts from the predictions.

4. **Geospatial Visualization**: Integrating geospatial visualization tools, such as GIS software or interactive maps, can provide a visual representation of the detected damaged areas overlaid on geographical data. This can aid in better understanding the spatial distribution of the damage and assist in decision-making for rescue and recovery operations.

5. **Uncertainty Estimation**: Incorporating uncertainty estimation techniques can provide a measure of confidence or reliability in the model's predictions. This can help in prioritizing the areas that require immediate attention or further inspection.

### Contribution
Contributions to this project are welcome. If you have any ideas for improvements or new features, please open an issue or submit a pull request. Together, we can enhance the accuracy and effectiveness of the building damage assessment machine learning model.

### License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT), which permits anyone to use, modify, and distribute the code for both commercial and non-commercial purposes.

### Acknowledgments
We would like to express our gratitude to the creators of the XBD dataset for providing a valuable resource for building damage assessment research. Their efforts have enabled us to develop this machine learning model and contribute to the field.
