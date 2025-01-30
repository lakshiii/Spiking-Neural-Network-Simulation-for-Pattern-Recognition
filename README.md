# Spiking-Neural-Network-Simulation-for-Pattern-Recognition
This repository implements a Spiking Neural Network (SNN) trained on the **Fashion-MNIST** dataset, which consists of 28x28 grayscale images of clothing items. The code uses **Brian2**, a Python library for simulating spiking neural networks, and leverages the **Leaky Integrate-and-Fire (LIF)** neuron model for simulation.
DataSet: www.kaggle.com/datasets/zalando-research/fashionmnist?resource=download 
### Features

- **Fashion-MNIST dataset**: This dataset contains 60,000 training images and 10,000 test images of fashion items, each represented as a 28x28 pixel grayscale image.
- **Poisson Spike Encoding**: Converts images into spike trains using a Poisson process to represent pixel intensities.
- **Leaky Integrate-and-Fire (LIF) Neuron Model**: Implements a simple LIF model for simulating excitatory neurons.
- **Synaptic Plasticity (STDP)**: Incorporates **Spike-Timing-Dependent Plasticity (STDP)** for synaptic weight adjustment based on the timing of spikes.
- **Training & Evaluation**: Trains the network on batches of Fashion-MNIST images and evaluates the performance on a small test set.

### Requirements

- **Python 3.x**
- **Brian2**: For simulating spiking neural networks.
- **NumPy**: For numerical computations.
- **Pandas**: For data loading and manipulation.
- **Matplotlib**: For plotting spike raster.

To install the necessary libraries, run:

```bash
pip install brian2 numpy pandas matplotlib
