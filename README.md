# Multi-Layer Perceptron (MLP) & Backpropagation

## 📌 Project Overview
This project explores **Multi-Layer Perceptrons (MLPs)** trained with **backpropagation** to classify data and approximate functions. The study focuses on **network architecture**, **hyperparameter tuning**, and the effects of **noise and regularization** on generalization.

## 🛠️ Technologies & Tools Used
- **Programming Language**: Python
- **Libraries**: NumPy, Scikit-Learn (MLPRegressor), Matplotlib
- **Learning Algorithm**: Backpropagation with Gradient Descent
- **Activation Functions**: Sigmoid (hidden layers), Linear (output layer)
- **Loss Metrics**: Mean Squared Error (MSE), Classification Accuracy

## 🔍 Key Features
- **Effect of Hidden Layers**: Analyzed different configurations (4, 8, 16, 32, 64 nodes).
- **Decision Boundary Visualization**: Evaluated classification performance on non-linearly separable data.
- **Function Approximation**: Modeled a **2D Gaussian function** with neural networks.
- **Time Series Prediction**: Applied a **three-layer perceptron** for **Mackey-Glass time series** forecasting.
- **Noise & Regularization**: Examined robustness using **weight decay** and **different architectures**.

## 📊 Results
✔️ **Increasing hidden nodes** improves classification accuracy but exhibits diminishing returns.  
✔️ **Function approximation with MLPs** successfully models smooth functions but struggles with sharp transitions.  
✔️ **For time series prediction**, a **(5,6) architecture** showed the best performance, balancing complexity and generalization.  
✔️ **Regularization (weight decay = 0.1)** improved noise robustness, preventing overfitting.
