# neuralnet-classifier

## Project Overview

The objective of this project is to build and train a neural network for a simple classification task: banknote authentication. The neural network architecture consists of an input layer with 4 neurons, one hidden layer with 10 neurons, and an output layer with 1 neuron. The objective is to determine the authenticity of banknotes based on their features.

## Dataset

We use the [Banknote Authentication dataset](https://archive.ics.uci.edu/ml/datasets/banknote+authentication) available at the UCI Machine Learning Repository. The dataset contains 1372 rows, each with 4 numerical features and 1 binary label. The features represent specific characteristics of banknotes, and the label indicates whether a banknote is genuine or counterfeit.

## Data Split

To train and evaluate the neural network, we split the dataset into three subsets:
- Training: 70% of the data is used for training the model.
- Validation: 20% of the data is reserved for model validation during training.
- Testing: The remaining 10% of the data is dedicated to testing the trained model's performance.

## Training Process

The training process involves the following key steps:
1. Data is divided into batches, with each batch containing 100 sample points.
2. The neural network is trained for a minimum of 10 epochs.
3. After each iteration (one batch), the backpropagation pass is executed to update the network's weights.
4. Validation is performed after each epoch to monitor the model's performance and prevent overfitting.
5. Testing is conducted once after the completion of the training process.

## Reporting Results

We report the following results to assess the neural network's performance:
- Training accuracy
- Validation accuracy
- Testing accuracy

Tables, graphs, and charts are used to visualize and present these accuracy metrics. The goal is to evaluate how well the neural network can classify banknotes as genuine or counterfeit based on the provided features.

## Matrix Notation

Matrix notation is employed to build and train the neural network efficiently. This approach simplifies the implementation of forward and backward passes, making the code more concise and easier to understand.

Feel free to explore the code and results in this repository to gain insights into the banknote authentication neural network's performance.
