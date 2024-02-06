# Diffusion Transformer Art Generation

This repository contains code for generating artistic images using the Diffusion Transformer model. The model is based on the [Stable Diffusion](https://github.com/huggingface/diffusers) pipeline and utilizes the [CetusMix V4](https://huggingface.co/redstonehero/cetusmix_v4) pre-trained model.

## Installation

Make sure to install the required dependencies before running the code. You can use the following commands:

```bash
!pip install diffusers["torch"] transformers
!pip install accelerate
!pip install git+https://github.com/huggingface/diffusers
