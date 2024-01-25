# Neural-Network-Regression
This project showcases a custom neural network implementation along with a TensorFlow-Keras model. 

## Dataset Overview

The dataset contains 700 entries with the following columns:

- **cement**: Amount of cement used in the mixture
- **water**: Amount of water used in the mixture
- **superplasticizer**: Amount of superplasticizer used in the mixture
- **age**: Age of the concrete (in days)
- **concrete_compressive_strength**: Target variable - Concrete compressive strength

## Exploratory Data Analysis

- Checked for missing values (none found).
- Checked data types and general statistics of the dataset.
- Visualized data distribution and correlation using boxplots and a heatmap.

## Data Preprocessing

- Performed feature scaling using standardization on input features.
- Implemented a manual train-test split function to split the dataset into training and testing sets.

## Neural Network Implementation

### Custom Neural Network (using NumPy)

- Created a custom neural network class with a configurable number of hidden layers.
- Implemented the sigmoid activation function for the hidden layer and linear activation for the output layer.
- Utilized mean squared error as the loss function.
- Trained the neural network on the training set, displaying the loss at regular intervals.

### Neural Network using TensorFlow

- Implemented a feedforward neural network using TensorFlow and Keras.
- Defined a custom callback to print the loss at specified intervals during training.
- Utilized the Adam optimizer and mean squared error loss function.
- Trained the neural network on the training set and evaluated on the test set.

## Model Evaluation

- Calculated and printed the training and testing loss for both custom and TensorFlow neural networks.
- Calculated the R-squared value for model performance assessment.

## Example Prediction

- Provided an example prediction for a new data point using the trained custom neural network.
