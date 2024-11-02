
# CGL-MHA: Lie Detection Model with GCN, LSTM, and Multi-Head Attention

This project implements a model for lie detection, integrating Graph Convolutional Networks (GCN), Long Short-Term Memory (LSTM) networks, and Multi-Head Attention (MHA). The primary objective is to enhance lie detection accuracy by leveraging the combined strengths of these neural network architectures.

## Project Structure

- **headlines/**: Contains the Python scripts implementing various models and configurations.
  - `CNN.py`: Convolutional Neural Network model.
  - `GRU.py`: Gated Recurrent Unit model.
  - `LSTM.py`: Long Short-Term Memory model.
  - `LSTM_GRU_CNN_MulA_Per.py`: Hybrid model using LSTM, GRU, CNN, and Multi-Head Attention.
  - `LSTM_GRU_MulA.py`: Combined model using LSTM, GRU, and Multi-Head Attention.
  - `SVM.py`: Support Vector Machine model for comparison.

- **requirements.txt**: Lists the Python dependencies required for running the code.

## Installation

1. **Clone the Repository**  
   Download the project files or clone the repository.

   ```bash
   git clone <repository-url>
   cd CGL-MHA-main
   ```

2. **Install Dependencies**  
   Use `pip` to install the required packages listed in `requirements.txt`.

   ```bash
   pip install -r requirements.txt
   ```

## Usage

Run the model scripts in the `headlines` directory based on your experimental requirements. For example, to run the LSTM-GRU-Multi-Head Attention model, use:

```bash
python headlines/LSTM_GRU_MulA.py
```

## Model Descriptions

- **GCN**: Graph Convolutional Networks help model the dependencies between nodes in a graph structure.
- **LSTM**: LSTM networks capture temporal dependencies in sequence data.
- **Multi-Head Attention**: The attention mechanism allows the model to focus on different parts of the input sequence, enhancing interpretability.

Each model script provides a unique approach to tackling the lie detection problem, allowing for flexible experimentation.

## Acknowledgments

This project incorporates techniques from neural networks and attention mechanisms to achieve robust results in lie detection tasks.
