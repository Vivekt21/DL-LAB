# Deep Learning Lab - Artificial Neural Network from Scratch

## Project Overview

This project implements a **Fully Connected Artificial Neural Network (ANN)** from scratch using only **NumPy** and **Matplotlib** (no deep learning libraries like TensorFlow or PyTorch). The goal is to understand the fundamental concepts of neural networks, backpropagation, and optimization by building and experimenting with a custom implementation.

## Project Scope

### Datasets
- **Pseudo Image 1**: 20x30 pixel images (600 features)
- **Pseudo Image 2**: 30x60 pixel images (1800 features)

### Experiments
The project involves systematic experimentation with:

1. **Activation Functions**
   - ReLU (Rectified Linear Unit)
   - Sigmoid
   - Tanh

2. **Learning Rates**
   - 0.001 (low)
   - 0.01 (medium)
   - 0.1 (high)
   - Custom values for fine-tuning

3. **Epoch Sizes**
   - Small: 10-50 epochs
   - Medium: 100-200 epochs
   - Large: 500+ epochs

## Dependencies

```
numpy          # Numerical computations
matplotlib     # Data visualization
python >= 3.7
```

### Installation

```bash
pip install numpy matplotlib
```

## Project Structure

```
DL LAB/
├── README.md                 # Project documentation
├── Mid Term/
│   ├── Midterm1.ipynb       # Experiment set 1 - ANN implementation and basic experiments
│   └── Midterm2.ipynb       # Experiment set 2 - Advanced experiments and comparisons
└── [utils/ or notebooks/]   # Additional helper files (if needed)
```

## Key Components

### 1. Neural Network Architecture

The custom ANN includes:

- **Forward Propagation**: Computing network output given input
- **Activation Functions**: Implementing ReLU, Sigmoid, Tanh, and Linear
- **Backward Propagation**: Computing gradients for all weights and biases
- **Gradient Descent**: Updating parameters to minimize loss
- **Loss Function**: Mean Squared Error (MSE) or Cross-Entropy

### 2. Hyperparameter Tuning

Each experiment combines:
- Different network architectures
- Various activation functions
- Multiple learning rates
- Different training durations (epochs)

### 3. Evaluation Metrics

- **Training Loss**: Loss over training iterations
- **Validation/Test Accuracy**: Model performance on unseen data
- **Convergence Speed**: How quickly the model learns
- **Final Performance**: Accuracy achieved after training

## Experiment Workflow

### Midterm 1: Foundation & Basic Experiments
- Implement ANN from scratch
- Build forward and backward propagation
- Test with simple activation functions (ReLU, Sigmoid)
- Establish baseline performance
- Visualize training curves

### Midterm 2: Advanced Experiments & Analysis
- Compare all activation functions systematically
- Test various learning rates
- Experiment with different epoch sizes
- Analyze impact of hyperparameters
- Generate comparative visualizations
- Document findings and observations

## How to Run

1. **Open Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

2. **Navigate to Mid Term folder** and open either `Midterm1.ipynb` or `Midterm2.ipynb`

3. **Run cells sequentially** to:
   - Build the neural network
   - Train on pseudo images
   - Visualize results
   - Compare experiments

## Expected Outputs

For each experiment, you should generate:

- **Training Curves**: Loss vs. epochs
- **Activation Function Comparison**: Performance metrics across different activations
- **Learning Rate Impact**: How different learning rates affect convergence
- **Epoch Analysis**: Training time vs. accuracy trade-offs
- **Visualizations**: Loss curves, accuracy plots, heatmaps of learned features

## Key Insights to Explore

1. **Activation Functions**: Which works best for your pseudo images?
2. **Learning Rate Sensitivity**: How does learning rate affect convergence speed?
3. **Overfitting**: Does increased epochs lead to overfitting?
4. **Trade-offs**: Balance between accuracy and training time
5. **Network Capacity**: How does network size impact learning?

## Useful Visualization Techniques

Using Matplotlib:
- Plot training/validation loss curves
- Create bar charts comparing activation functions
- Generate heatmaps of learned weights
- Visualize pseudo image samples
- Compare convergence speeds

## References

- **Backpropagation**: The chain rule for computing gradients
- **Gradient Descent**: Optimization algorithm for updating weights
- **Activation Functions**: Non-linear transformations for neural networks
- **Loss Functions**: Metrics to minimize during training

## Notes

- This implementation prioritizes **understanding** over performance
- Focus on how hyperparameters affect learning dynamics
- Document observations and create visualizations for each experiment
- Use this as a foundation for understanding deeper learning concepts

## Author

Deep Learning Lab - Experimental Study on Neural Networks

