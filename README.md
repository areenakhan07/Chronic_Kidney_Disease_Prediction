# NephroVision

This project is dedicated to building machine learning models to predict the presence or absence of chronic kidney disease in patients. By leveraging diverse features and medical data, this project aims to develop precise classification models that can effectively identify kidney disease in individuals.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Data](#data)
- [Features](#features)
- [Models](#models)
- [Contributing](#contributing)

## Introduction
Chronic kidney disease can pose significant health risks, including the potential development of kidney failure and related complications when not addressed promptly. The importance of early detection lies in its ability to facilitate timely intervention and effective management, which may help prevent or delay the advancement of the disease, ultimately leading to improved outcomes for patients. By building accurate machine learning models, this project analyzes relevant medical data and accurately classifies whether a patient is afflicted by a chronic kidney disease or not.

## Installation
To use this project, clone the repository and install the required dependencies using the following command:

pip install -r requirements.txt

## Data
This project utilizes medical data related to patients,  with and without chronic kidney disease. The dataset contains various features such as age, blood pressure, serum creatinine levels, and other medical indicators. It is important to ensure that the dataset is properly cleaned and prepared before running the project. The `kidney_disease.csv` file contains the dataset used for analysis and prediction.

## Features
- Data Preprocessing: This project includes modules to preprocess and clean the medical data, ensuring that it is ready for analysis and model training.
- Data Visualization: Various visual techniques are employed to gain insights into the data and identify potential patterns or correlations related to chronic kidney disease.
- Machine Learning Models: This project utilizes classification machine learning algorithms to predict the presence or absence of chronic kidney disease in patients.
- Evaluation and Metrics: Different evaluation metrics are used to assess the performance of the machine learning models and measure their accuracy in predicting chronic kidney disease.

## Models
This project employs several classification machine learning models, including:
- KNN
- Decision Tree
- Random Forest Classifier

To determine the effectiveness of each model, suitable metrics are employed to evaluate their performance. This evaluation process enables the identification of the most effective model, which can then be used for future predictions.

## Contributing
Contributions to this project are welcome. If you find any bugs, have feature requests or want to contribute improvements, please submit an issue or a pull request. Your engagement and input are highly valued.
