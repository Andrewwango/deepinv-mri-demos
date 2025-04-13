# deepinv-mri-demos
Demos for accelerated MRI reconstruction with deep learning using DeepInverse.

By [Andrew Wang](https://andrewwango.github.io)

We demonstrate three types of methods:

1. [Plug-and-play with a pretrained denoiser](#1-plug-and-play-with-a-pretrained-denoiser)
2. [Self-supervised unrolled learning](#2-self-supervised-feedforward-learning)
3. [Posterior sampling from a diffusion model](#3-posterior-sampling-from-a-diffusion-model)

Find the demo in the [demo notebook](demo.ipynb).

## Get started

- Create a Python environment: `python -m venv venv`
- Download `deepinv`: `pip install deepinv`
- Start a notebook server (Jupyter, VSCode, Colab...)
- Download the FastMRI subset file [here](https://huggingface.co/datasets/deepinv/images/blob/f629d3e2d4a5d63f5e081835bd1d6338fee8077f/fastmri_knee_singlecoil.pt).