# CVD Disease Prediction using Machine Learning

This project implements machine learning models to predict cardiovascular disease (CVD) using various features such as age, blood pressure, cholesterol levels, and other health indicators.

## Overview

The project uses two main machine learning approaches:
- **Random Forest Classifier**: An ensemble learning method
- **Artificial Neural Network (ANN)**: Deep learning approach using TensorFlow/Keras

## Features

- Exploratory Data Analysis (EDA) with visualizations
- Data preprocessing and feature engineering
- Outlier detection and removal
- Clustering analysis using K-Modes
- Model comparison with performance metrics
- ROC curve analysis and AUC scores

## Dataset

The project uses a cardiovascular disease dataset with the following features:
- Age, Gender, Height, Weight
- Blood pressure (systolic and diastolic)
- Cholesterol levels
- Glucose levels
- Smoking, Alcohol consumption
- Physical activity
- Target variable: Cardiovascular disease presence (0/1)

## Requirements

- Python 3.7+
- pandas
- numpy
- scikit-learn
- tensorflow
- matplotlib
- seaborn
- kmodes

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/CVD_Prediction.git
cd CVD_Prediction
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

## Usage

1. Open the Jupyter notebook: `CVD__Disease_Prediction_ML_using_ML.ipynb`
2. Make sure you have the dataset file `cardio_train.csv` in the appropriate directory
3. Run all cells to execute the complete analysis

## Results

The models achieve the following performance:
- Random Forest: High accuracy with good generalization
- ANN: Competitive performance with deep learning approach

## Project Structure

```
CVD_Prediction/
├── CVD__Disease_Prediction_ML_using_ML.ipynb  # Main analysis notebook
├── Machine Learning Final Report.pdf          # Project report
├── requirements.txt                           # Python dependencies
├── README.md                                 # This file
└── .gitignore                               # Git ignore file
```

## Contributing

Feel free to fork this project and submit pull requests for any improvements.

## License

This project is open source and available under the MIT License.
