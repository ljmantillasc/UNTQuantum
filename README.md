# NEQR Quantum Circuit Example

**Author: Luis Jose Mantilla Santa Cruz**

This repository contains a Jupyter Notebook implementing a quantum circuit for the Novel Enhanced Quantum Representation (NEQR) model using Qiskit. The notebook demonstrates how to encode a small 2x2 grayscale image into a quantum state and simulate the results.

## Overview

The NEQR (Novel Enhanced Quantum Representation) model is a method for representing digital images in a quantum format. This model improves upon previous methods by using quantum superposition and entanglement to encode both pixel intensity and coordinates efficiently. 

In this notebook, we:
- Define a quantum circuit for encoding a 2x2 grayscale image.
- Apply Hadamard and CNOT gates to put qubits into superposition and entangle them.
- Simulate the quantum circuit and visualize the results.

## Getting Started

To get started with this notebook, follow these steps:

### Prerequisites

Make sure you have the following installed:
- Python 3.x
- Jupyter Notebook
- Qiskit (Quantum computing SDK for Python)

You can install Qiskit using pip:

```bash
pip install qiskit
