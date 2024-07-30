# Breast_Cancer_Prediction-with-ANN

This repository contains the code and documentation for predicting breast cancer using an Artificial Neural Network (ANN). The model was trained and tested on a dataset with 569 samples and achieved an accuracy of 97.3% on the test dataset.

## Dataset

The dataset used in this project consists of 569 samples with the following features:

- mean_radius
- mean_texture
- mean_perimeter
- mean_area
- mean_smoothness
- mean_compactness
- mean_concavity
- mean_concave_points
- mean_symmetry
- mean_fractal_dimension
- radius_error
- texture_error
- perimeter_error
- area_error
- smoothness_error
- compactness_error
- concavity_error
- concave_points_error
- symmetry_error
- fractal_dimension_error
- worst_radius
- worst_texture
- worst_perimeter
- worst_area
- worst_smoothness
- worst_compactness
- worst_concavity
- worst_concave_points
- worst_symmetry
- worst_fractal_dimension
- label (target variable: 0 for benign, 1 for malignant)

## Model

An Artificial Neural Network (ANN) was built to predict whether a tumor is benign or malignant based on the provided features. The model architecture, training, and evaluation steps are detailed in the accompanying Jupyter notebook.

## Results

The model achieved an accuracy of **97.3%** on the test dataset.

## Installation

To run this project, you need to have Python installed along with the following libraries:

- pandas
- numpy
- scikit-learn
- tensorflow
- matplotlib

You can install the required libraries using pip:

```bash
pip install pandas numpy scikit-learn tensorflow matplotlib
```

## Usage

1. Clone this repository:

```bash
git clone https://github.com/yourusername/breast-cancer-prediction-ann.git
```

2. Navigate to the project directory:

```bash
cd breast-cancer-prediction-ann
```

3. Open the Jupyter notebook:

```bash
jupyter notebook Breast_Cancer_Prediction.ipynb
```

