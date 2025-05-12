# Layer Cake Model Project

This repository contains a machine learning project that implements and evaluates different neural network architectures, including a baseline model and a layer cake model approach.

## Project Structure

- `Baseline.ipynb`: Contains the implementation and evaluation of the baseline neural network model
- `Layer_Cake_Model.ipynb`: Implements the layer cake architecture approach
- `Sliding_Window_Benchmark.ipynb`: Contains benchmarking code using a sliding window approach
- `policy_net_weights.pth`: Saved weights for the policy network
- `target_net_weights.pth`: Saved weights for the target network

## Requirements

The project uses Python and requires the following key dependencies:
- PyTorch
- Jupyter Notebook
- GPU support (A100 recommended)

## Usage

1. Clone this repository
2. Install the required dependencies
3. Open the Jupyter notebooks in order:
   - Start with `Baseline.ipynb` to understand the base implementation
   - Explore `Layer_Cake_Model.ipynb` for the layer cake architecture
   - Use `Sliding_Window_Benchmark.ipynb` for performance evaluation

## Model Weights

The repository includes pre-trained model weights:
- `policy_net_weights.pth`: Contains the weights for the policy network
- `target_net_weights.pth`: Contains the weights for the target network

These weights can be loaded to reproduce results or continue training from a saved state.

## Note

This project was developed with GPU acceleration in mind, specifically optimized for A100 GPUs. Make sure you have the appropriate hardware and drivers installed for optimal performance. 