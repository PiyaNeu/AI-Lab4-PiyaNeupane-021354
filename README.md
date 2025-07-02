# Artificial Neural Networks: Perceptron

This project explores the implementation of a **single-layer perceptron** to approximate linear functions using synthetic data. Two versions are presented:

- A perceptron model trained on 3 specific features
- A flexible perceptron model that works with any number of features

---

## Project Files

| File Name                | Description                                                 |
|-------------------------|-------------------------------------------------------------|
| `perceptron_3_features.py` | Trains a perceptron using 3 manually defined input features      |
| `perceptron_n_features.py` | Allows user to train a perceptron on n-dimensional input data     |

---

### 1️⃣ Perceptron with 3 Inputs

- **Function to Learn**:  
y = 2x₁ + 3x₂ + x₃ + 5

- **Number of Features**: 3
- **Learning Rate**: 0.01
- **Outputs**:
- Final learned weights
- Bias term
- Mean Squared Error (MSE) after training

---

### 2️⃣ Perceptron with n Inputs

- **Function to Approximate**:  

y = w₁x₁ + w₂x₂ + ... + wₙxₙ + b

- **Number of Features**: Customizable (user-defined)
- **Weights**: Initialized randomly
- **Outputs**:
- Final weights and bias
- Training error (e.g., MSE)

---

## 🔧 Requirements

Ensure the following packages are installed:

- Python 3.6 or higher
- NumPy
- Matplotlib
- scikit-learn (used only for PCA in a separate K-Means visualization task)

Install all dependencies via:

```bash
pip install numpy matplotlib scikit-learn
python perceptron_3_features.py
python perceptron_n_features.py

