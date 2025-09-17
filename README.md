# Flow Matching from Scratch

This repository is an attempt at understanding (conditional) flow matching for generative modeling with notebooks containing a write-up of my implementation and things that might not be intuitive.

## Overview

The following references are primarily used for the mentioned notebooks.

*FM from scratch <[notebook](notebooks/from_scratch.ipynb)>*
- [Flow Matching for Generative Modeling, 2023 by Y. Lipman *et al.*](https://arxiv.org/abs/2210.02747)
- [Flow Matching Guide and Code, 2024 by Y. Lipman *et al.*](https://arxiv.org/abs/2412.06264)
- [flow_matching PyTorch library by FAIR](https://github.com/facebookresearch/flow_matching)

*Conditioning <[notebook](notebooks/conditioning.ipynb)>*
- [TorchCFM](https://github.com/atong01/conditional-flow-matching)

*Latents <[notebook](notebooks/latents.ipynb)>*
- TODO, how you start from something else than a standard Gaussian (e.g latent obtained from VAE encoder)
* (extra) *GSplat flows <notebook, todo>*

*(GC)Reinforcement learning <[notebook](notebooks/rl.ipynb)>*
- TODO, bridge this technique to (GC)RL (still with toy envs.)
