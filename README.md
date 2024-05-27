# Parallel Feature Fusion Network for Autism Detection


## Overview

This repository contains the implementation of a deep learning image classifier designed to differentiate between Autism Spectrum Disorder (ASD) and Typical Development (TD). The classifier employs a dual-track feature fusion network architecture that combines a Swin Transformer with a customized Convolutional Neural Network (CNN), achieving a remarkable classification accuracy of 98.7%. Additionally, a Quantum Support Vector Machine (QSVM) is utilized for feature classification, operating on a quantum simulator with 16 qubits, and attaining a classification accuracy of 96%.

## Architecture

### 1. Dual-Track Feature Fusion Network
- **Swin Transformer**: Excels in capturing long-range dependencies within images, facilitating a deeper understanding of the interrelations among different image components.
- **Customized CNN**: Specializes in extracting local features, contributing to improved classification performance by considering both local and global features.

### 2. Quantum Support Vector Machine (QSVM)
- Utilizes features extracted from the feature fusion network.
- Operates on a quantum simulator with 16 qubits.
- Achieves a classification accuracy of 96%.
- Leverages quantum computing to potentially accelerate predictions, reduce computational time, and enhance overall efficiency.

## Results
- **Feature Fusion Network**: 98.7% classification accuracy.
- **QSVM**: 96% classification accuracy.

## Prerequisites

Ensure you have the following software and libraries installed:
- Python 3.x
- PyTorch
- TensorFlow
- Qiskit (for quantum simulations)
- NumPy
- SciPy
- scikit-learn
- Matplotlib

