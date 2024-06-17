<img src="img/logo.png" width="100" height="100">

# Biological-Neural-Network-Simulations
This repository contains Jupyter Notebooks that simulate various neural networks using biologically plausible models. The simulations use spiking neural networks (SNNs) with detailed explanations linking the computational models to biological concepts.


## Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Notebooks](#notebooks)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The purpose of this repository is to provide educational and research-oriented Jupyter Notebooks that model different regions of the brain using spiking neural networks. These models incorporate realistic neuron dynamics, synaptic plasticity mechanisms like spike-timing-dependent plasticity (STDP), and network connectivity patterns found in the brain.

## Installation

To run the notebooks in this repository, you need to have Python installed along with the following packages:

- Brian2
- NumPy
- Matplotlib

You can install these packages using `pip`:

```bash
pip install brian2 numpy matplotlib
```


## Notebooks

### 1. Hippocampal CA3 Region Model
This notebook simulates a simplified version of the hippocampal CA3 region using spiking neural networks. The model includes both excitatory and inhibitory neurons, with synaptic plasticity based on STDP.

[Link to Notebook](notebooks/hippocampus_ca3.ipynb)

## Contributing

Contributions are welcome! If you have any suggestions, improvements, or new models to add, please create a pull request or open an issue.

### Steps to Contribute

1. Fork the repository
2. Create a new branch: `git checkout -b feature-branch`
3. Make your changes and commit them: `git commit -m 'Add new feature'`
4. Push to the branch: `git push origin feature-branch`
5. Submit a pull request

## License

This repository is licensed under the MIT License. See the LICENSE file for more details.

