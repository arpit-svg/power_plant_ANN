⚡ Power Plant Energy Prediction using PyTorch ANN
📌 Overview

This project implements an Artificial Neural Network (ANN) using PyTorch to predict electrical power output (PE) of a Combined Cycle Power Plant.

The model learns the relationship between environmental variables and power generation.

📊 Features Used

AT → Ambient Temperature

V → Exhaust Vacuum

AP → Ambient Pressure

RH → Relative Humidity

PE → Electrical Power Output (Target Variable)

🎯 Objective

To build a regression-based ANN model using PyTorch that accurately predicts power output based on atmospheric conditions.

🧠 Model Architecture

Input Layer → 4 neurons

Hidden Layers → Fully Connected (Linear layers)

Activation Function → ReLU

Output Layer → 1 neuron (Regression output)

Loss Function → Mean Squared Error (MSELoss)

Optimizer → Adam

⚙️ Project Pipeline

Data Loading (Pandas)

Data Preprocessing

Train-test split

Feature scaling (StandardScaler)

Conversion to PyTorch Tensors

Model Definition using torch.nn.Module

Training Loop Implementation

Forward pass

Loss computation

Backpropagation (loss.backward())

Optimizer step

Model Evaluation

📊 Results

Model evaluated using:

Mean Squared Error (MSE)

R² Score

The ANN successfully captures nonlinear relationships between environmental variables and electrical output.
