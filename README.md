# Signal Denoising with Autoencoder

## Overview
This project focuses on generating noisy signals and utilizing an autoencoder model to denoise the signals, restoring them to their original, noise-free state.

## Project Structure
The project includes the following components:
- **Generate_pulses.ipynb**: Notebook for generating noisy signals.
- **Denoising_signals.ipynb**: Notebook for training the autoencoder model and denoising the signals.

## Notebooks
1. **Generate_pulses.ipynb**:
    - This notebook is responsible for generating the noisy signals.
    - It creates synthetic signals and adds various types and levels of noise to simulate real-world scenarios.

2. **Denoising_signals.ipynb**:
    - This notebook focuses on training an autoencoder model.
    - The trained autoencoder is used to denoise the previously generated noisy signals, aiming to restore them to their original state.

## Model
- **Autoencoder**: An unsupervised neural network model used for denoising signals. It consists of an encoder that compresses the input signal and a decoder that reconstructs the signal from the compressed representation.

## Usage
1. **Generate Noisy Signals**:
    - Open and run the `Generate_pulses.ipynb` notebook.
    - This will generate synthetic signals and add noise to them, saving the noisy signals for later use.

2. **Train Autoencoder and Denoise Signals**:
    - Open and run the `Denoising_signals.ipynb` notebook.
    - This notebook will train an autoencoder on the noisy signals and use it to denoise the signals, comparing the denoised output with the original, noise-free signals.

## Adding Files to the Repository
When adding the files to the repository, include a brief description for each file to make it clear what they contain and their purpose:
- `Generate_pulses.ipynb`: Notebook for generating synthetic signals and adding noise to them.
- `Denoising_signals.ipynb`: Notebook for training the autoencoder model and denoising the generated noisy signals.

## Conclusion
This project demonstrates the use of an autoencoder model for denoising signals. By generating synthetic noisy signals and applying the autoencoder, we can effectively restore the signals to their original, noise-free state.

