---
layout: post
title:  "Welcome to Jekyll!"
---

# Introduction to Deep Learning

### **Motivation for Deep Learning**

- Eliminates the need for manual feature extraction.

### **Why Deep Learning is Prevalent Now**

1. **Big Data:** Availability of large datasets.
2. **Hardware Progress:** Enhancements in hardware, especially those that are massively parallelizable.
3. **Software Advancements:** Development of efficient software, e.g., TensorFlow.

### **Understanding the Perceptron**

- A perceptron is a single neuron used for forward propagation.
- **Components:**
    1. **Inputs**
    2. **Weights**
    3. **Summation**
    4. **Non-Linearity (Activation Functions):**
        - Common functions include:
            1. **`tf.math.sigmoid`**
            2. **`tf.math.tanh`**
            3. **`tf.nn.relu`**
        - **Purpose:** To model real-world non-linearities.
    5. **Output**

### **From Perceptron to Neural Network**

- **Dense Layer:** Basic building block (**`tf.keras.layers.Dense(units)`**).
- **Sequential Model:** **`model = tf.keras.Sequential([layers])`**.
- **Concept:** Stacking multiple layers forms a deep neural network.

### **Training a Deep Learning Model**

1. **Loss Function:**
    - Examples: **`cross_entropy_with_logits`** (for binary classification), Mean Squared Error (MSE).
2. **Loss Optimization (Backpropagation):**
    - **Learning Rate:** Balancing exploration and exploitation.
    - **Gradient Descent Algorithms:**
        1. Stochastic Gradient Descent (SGD)
        2. Adam
        3. Adadelta
        4. Adagrad
        5. RMSProp
    - **Mini-batches:** For efficient training.
3. **Avoiding Overfitting:**
    - **Regularization Techniques:**
        1. Dropout
        2. Early Stopping