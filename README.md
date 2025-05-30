# home_assignment1_neural-network

# CS5720 Neural Networks and Deep Learning
## Home Assignment 1 – Summer 2025

**Student Name:** [gudiseva charan santhosh]
**student id:** [700776700]  

**Course:** CS5720 – Neural Networks and Deep Learning  
**University:** University of Central Missouri  

---

## Assignment Overview

This assignment covers:

1. **Tensor Manipulations** using TensorFlow
2. **Loss Function Comparison** (MSE vs CCE)
3. **Neural Network Training** with MNIST
4. **Logging with TensorBoard**


### 🔹 Tensor Reshaping
- Created a random tensor of shape (4, 6)
- Found its rank and shape
- Reshaped to (2, 3, 4) and transposed to (3, 2, 4)
- Performed broadcasting with shape (1, 4)

### 🔹 Loss Functions
- Compared Mean Squared Error (MSE) and Categorical Cross-Entropy (CCE)
- Plotted loss values in a bar chart

### 🔹 Neural Network
- Trained a model on MNIST dataset (5 epochs)
- Used TensorBoard for monitoring training and validation

---

## 📈 TensorBoard Log Directory
Logs are stored in:
```
logs/fit/
```

To launch TensorBoard:
```bash
tensorboard --logdir=logs/fit
```


---

##  Notes
- Make sure to `pip install tensorflow matplotlib` if not already installed.
---

