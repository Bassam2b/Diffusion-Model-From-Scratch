# Diffusion-Model-From-Scratch
Implementing a diffusion probabilistic model from scratch with PyTorch, trained on the Stanford Cars dataset using a simplified U-Net architecture.

This project implements a diffusion generative model from scratch in PyTorch, following the forward–backward diffusion process with a simplified U-Net. The model is trained on the Stanford Cars dataset, learning to generate realistic images from pure noise.

Key Features

Dataset: Stanford Cars (automatically downloaded via torchvision)

Forward diffusion: gradually noising images using a linear beta schedule

Backward diffusion: U-Net model reconstructing images step by step

Architecture: simplified U-Net with sinusoidal time embeddings

Training: 100 epochs with Adam optimizer

Sampling: progressive denoising visualizations across timesteps

Results:

Visualizes how images evolve from noise to clear samples

Demonstrates the effectiveness of diffusion-based generative modeling

Provides a foundation for experimenting with DDPMs, DDIMs, and Stable Diffusion variants
