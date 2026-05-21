# Artificial Neural Networks & Deep Learning Foundations

This directory contains the comprehensive, publication-quality lecture notes and analytical frameworks for the **Artificial Neural Networks & Deep Learning Foundations** curriculum. 

The primary artifact is a programmatically compiled PDF reference guide (`ANN.pdf`) engineered to bridge structural theory with foundational optimization mathematics.

---

## 📂 File Registry

### 1. `ann.pdf`
The main compiled study guide. It avoids dense walls of text by utilizing structured performance comparison matrices, analytical equations, and native visual vector graphics.

---

## 📝 Document Index & Core Concepts

The PDF breaks down the deep learning syllabus across the following strategic modules:

*   **1. What is Deep Learning & Deep Learning Fundamentals**
    *   *Core Concepts:* The architectural shift from manual feature engineering to automated feature hierarchy learning across stacked hidden layers[cite: 2].
*   **2. How Do Artificial Neurons Work? A Complete Guide**
    *   *Core Concepts:* Biological synapse modeling using the Perceptron framework. Explains the step-by-step linear combination stage ($z = \sum w_i x_i + b$) and subsequent non-linear activation transformations ($y = f(z)$)[cite: 2].
*   **3. Activation Functions Explained: ReLU, Sigmoid, Tanh & Threshold**
    *   *Core Concepts:* A centralized comparison matrix highlighting functional ranges, derivative mechanics, and primary use cases[cite: 2]. Includes a deep dive into the **Dying ReLU Phenomenon** (and how Leaky ReLU preserves gradient flows)[cite: 2].
*   **4. How Do Neural Networks Work? Step-by-Step Property Valuation**
    *   *Core Concepts:* A concrete real-world scenario demonstrating how abstract feature vectors (Area, Bedrooms, Transit Proximity, Crime Rating) organically synthesize higher-level conceptual abstractions within hidden layer nodes to output a property valuation[cite: 2].
*   **5. How Do Neural Networks Learn? Cost Functions & Backpropagation**
    *   *Core Concepts:* Formulating performance errors using Mean Squared Error (MSE)[cite: 2]. Step-by-step documentation of backpropagation using the mathematical **Chain Rule** to compute partial derivatives (gradients) of the cost function with respect to weights and biases[cite: 2].
*   **6. Understanding Gradient Descent Optimization**
    *   *Core Concepts:* Mathematical update mechanics ($w_{\text{new}} = w_{\text{old}} - \alpha \frac{\partial J}{\partial w_{\text{old}}}$) and the critical hyperparameter management of the learning rate ($\alpha$) to prevent oscillation or premature convergence[cite: 2].
*   **7. Stochastic (SGD) vs. Batch Gradient Descent**
    *   *Core Concepts:* Comparative analysis of operational data batching methodologies, evaluating the structural trade-offs between memory footprints, computing speeds, and convergence trajectories[cite: 2].

---

## 🎨 Architectural Visuals & Layout Specifications

The document was compiled to standard `A4` page margins ($20\text{mm} \times 15\text{mm}$) using highly legible typography and includes two embedded high-fidelity vector diagrams:
1.  **Figure 1 (Fully Connected Architecture):** Visual mapping of forward synaptic connection pathways streaming across input nodes, sequential deep hidden stacks, and output boundaries[cite: 2].
2.  **Figure 2 (Mathematical Schema of a Neuron):** A technical look inside a node, tracing inputs through weight scaling vectors, the summation core ($\sum$), bias injections ($b$), and non-linear function filters ($f(z)$)[cite: 2].
3.  **Accent Formatting:** Important warnings—such as dead weight adjustments—are highlighted inside high-contrast amber callout boxes (`#FFFAF0`) to facilitate quick review intervals[cite: 2].
