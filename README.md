# Neural Network Frequency Filter

This project explores using a neural network to generate a filter for a single interfering frequency. It was initially developed as a quick experiment during a meeting (in which I was really bored) but has the potential for further development into a more comprehensive signal processing tool.

## Features
- Neural network-based filtering of single interfering frequencies.
- Visualizes both the time-domain signal and frequency response using FFT.
- Utilizes PyTorch for the neural network implementation.

## Getting Started

### Requirements
Ensure you have Python 3.x installed. Required libraries can be installed using the `requirements.txt` file provided.

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/agowd/neural_dsp.git
   cd neural_dsp
   ```
2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

### Usage
- Open `neural_dsp.ipynb`.
- Run the notebook cells to visualize the filtering process and experiment with different signals.

## Future Plans
- Extend the network to filter multiple interfering frequencies.
- Explore real-time filtering capabilities.

## License
MIT License

