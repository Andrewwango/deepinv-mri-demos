# deepinv-mri-demos
Demos for accelerated MRI reconstruction with deep learning using DeepInverse.

By [Andrew Wang](https://andrewwango.github.io)

We demonstrate three types of methods:

1. Plug-and-play with a pretrained denoiser [\[1\]](#references)
2. Self-supervised unrolled learning using Equivariant Imaging [\[2, 3\]](#references)
3. Posterior sampling from a diffusion model using DPS [\[4\]](#references)

Find the demo in the [demo notebook](demo.ipynb).

## Get started

- Create a Python environment: `python -m venv venv`
- Download `deepinv`: `pip install deepinv`
- Start a notebook server (Jupyter, VSCode, Colab...)
- Download the FastMRI subset file [here](https://huggingface.co/datasets/deepinv/images/blob/f629d3e2d4a5d63f5e081835bd1d6338fee8077f/fastmri_knee_singlecoil.pt).

## References

- [1] Zhang et al., [_"Plug-and-Play Image Restoration with Deep Denoiser Prior"_](https://arxiv.org/abs/2008.13751)
- [2] Chen D., Tachella J. & Davies M., [_"Equivariant Imaging: Learning Beyond the Range Space"_](https://arxiv.org/abs/2103.14756)  
- [3] Wang A. & Davies M., [_"Fully unsupervised dynamic MRI reconstruction"_](https://arxiv.org/abs/2410.08646)
- [4] Chung et al., [_"Diffusion Posterior Sampling for General Noisy Inverse Problems"_](https://arxiv.org/abs/2209.14687)