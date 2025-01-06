


# Neural-Network-Regression

This repository contains a neural network regression model implemented in Python. The model is designed to predict the compressive strength of concrete based on various features.

## Table of Contents
- [Neural-Network-Regression](#neural-network-regression)
  - [Table of Contents](#table-of-contents)
  - [Project Overview](#project-overview)
  - [Repository Structure](#repository-structure)
  - [Dataset](#dataset)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Model Details](#model-details)
  - [Results](#results)
  - [License](#license)
  - [Acknowledgements](#acknowledgements)

## Project Overview
The project demonstrates the use of a neural network for regression tasks. The target variable is the compressive strength of concrete, and the features include cement, water, superplasticizer, and age.

## Repository Structure
```
Neural-Network-Regression/
│
├── code.ipynb                 # Jupyter notebook containing the implementation
├── concrete_data.xlsx         # Dataset used for training and testing the model
├── LICENSE                    # License file
├── README.md                  # Readme file
├── requirements.txt           # Dependencies required for the project
└── Soft Computing - Assignment 4.pdf # Project requirements
```

## Dataset
The dataset used in this project (concrete_data.xlsx) contains the following features:
- Cement
- Water
- Superplasticizer
- Age
- Concrete Compressive Strength

## Installation
To install the required dependencies, run:
```bash
pip install -r requirements.txt
```

## Usage
1. Clone the repository:
```bash
git clone https://github.com/RanaEssam03/Neural-Network-Regression.git
```
2. Navigate to the repository directory:
```bash
cd Neural-Network-Regression
```
3. Open the `code.ipynb` notebook and run the cells to train and evaluate the neural network model.

## Model Details
The neural network model is implemented using Python and consists of:
- Input layer with 4 neurons (corresponding to the 4 features)
- Hidden layer with 8 neurons
- Output layer with 1 neuron (regression output)

The model uses the sigmoid activation function and the Mean Squared Error (MSE) as the loss function. The training is performed using backpropagation with a learning rate of 0.02.

## Results
The model's performance on the test set is as follows:
- Test MSE: 0.004169806529974958
- Test Accuracy: 0.995830193470025
- R2 Score: 0.8413254765720553

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements
This project is part of the Soft Computing course.
