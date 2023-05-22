# Sonic Wave Velocity Prediction using AutoML
==============================
                                                                    
This repository contains code and resources for predicting sonic wave velocities using Automated Machine Learning (AutoML) techniques. The goal is to automate the process of predicting sonic wave velocities based on various well log measurements.

## Dataset
The prediction of sonic wave velocities is performed using the following variables:

- CAL - Caliper, unit in Inch
- CNC - Neutron, unit in dec
- GR - Gamma Ray, unit in API
- HRD - Deep Resistivity, unit in Ohm per meter
- HRM - Medium Resistivity, unit in Ohm per meter
- PE - Photo-electric Factor, unit in Barn
- ZDEN - Density, unit in Gram per cubic meter
- DTC - Compressional Travel-time, unit in nanosecond per foot (label)
- DTS - Shear Travel-time, unit in nanosecond per foot (label)
These variables serve as inputs for the machine learning models to predict the compressional (DTC) and shear (DTS) travel-times..

## AutoML Frameworks
Two AutoML frameworks were utilized for the prediction task:

1. EvalML: EvalML is an open-source Python library developed by Alteryx that simplifies the machine learning workflow. It automatically performs data preprocessing, feature engineering, model selection, and hyperparameter optimization.

2. PyCaret: PyCaret is an open-source low-code machine learning library in Python that automates the end-to-end machine learning process. It provides a wide range of pre-processing techniques, feature selection methods, and model training algorithms

## Best ML Algorithms
After running the AutoML frameworks, the best machine learning algorithms for the sonic wave velocity prediction task were identified:

1. XGBoost: XGBoost is a popular gradient boosting framework that excels in handling structured data. It utilizes an ensemble of decision trees to make accurate predictions.

2. ExtraTreesRegressor: ExtraTreesRegressor is an ensemble learning method that combines multiple randomized decision trees to achieve robust and accurate regression predictions.

## Requirements
The following Python packages are required to run this model:

1. Pycaret
2. pandas
3. numpy
4. scikit-learn
5. joblib
6. flask
7. EvalML
8. Matplotlib

You can Install the necessary dependencies ```pip install -r requirements.txt``` in the command line.

## Usage

**Clone this repository to your local machine.**
```bash
git clone https://github.com/obinopaul/Sonic-Wave-Velocity-Prediction-using-AutoML.git                                        
```

"#Pore_Pressure_Prediction_for_Oil_and_Gas" 