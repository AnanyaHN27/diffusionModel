# Diffusion Model Implementation

This notebook implements a diffusion model from scratch, inspired by [this guide](https://erdem.pl/2023/11/step-by-step-visual-introduction-to-diffusion-models). The goal of this project is to demonstrate the process of building and training a basic diffusion model on the MNIST dataset without any pre-trained models or specialized purposes.

## Contents

- **Introduction**: A diffusion model is a type of generative model that learns to reverse a noising process applied to data, here demonstrated on MNIST images.
- **Architecture**: This implementation follows the architecture and methodology described in the linked guide, providing insight into how diffusion models work on a fundamental level.

## Getting Started

### Prerequisites

Ensure you have the following libraries installed:
- `tensorflow`
- `numpy`
- `tqdm`

You can install these using:
```bash
pip install tensorflow numpy tqdm
