---
title: Survey list of diffusion models
subtitle: I'm interested in diffusion models, this is a paper list.

# Summary for listings and search engines
summary: Paper list of diffusion models.

# Link this post with a project
projects: []

# Date published
date: '2022-07-01T00:00:00Z'

# Date updated
lastmod: '2022-07-01T00:00:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'general diffusion process'
  focal_point: ''
  placement: 2
  preview_only: false

authors:
  - admin

tags:
  - diffusion model

categories:
  - paper list
---

### Classical model (unconditional)
1. Diffusion original 

- Jascha Sohl-Dickstein et al. “Deep Unsupervised Learning using Nonequilibrium Thermodynamics.” ICML 2015.

2. NCSN and NCSNv2 (noise-conditioned score network)
Score-based generative modeling + Langevin dynamics

- Yang Song & Stefano Ermon. “Generative modeling by estimating gradients of the data distribution.” NeurIPS 2019. 

- Yang Song & Stefano Ermon. “Improved techniques for training score-based generative models.” NeurIPS 2020.  (for higher resolution)

3. DDPM

- Jonathan Ho et al. “Denoising diffusion probabilistic models.” NeurlPS 2020. 

- Alex Nichol & Prafulla Dhariwal. “ Improved denoising diffusion probabilistic models” ICML 2021.  (ImageNet)

4. DDIM non- Markov chain to speed up

-  Jiaming Song et al. “Denoising diffusion implicit models.” ICLR 2021. 

### Domain
1. Image

- Prafula Dhariwal & Alex Nichol. "Diffusion Models Beat GANs on Image Synthesis." NeurIPS 2021. 

2. Time series

- Yang Song, CSDI: Conditional Score-based Diffusion Models for Probabilistic Time Series Imputation, NeurIPS, 2021

3. Text

- Nikolay Savinov, Aaron van den Oord. "Step-unrolled Denoising Autoencoders for Text Generation." ICLR 2022. [SUNDAE code non-official] (baseline: Disco, CMLM)

- Emiel Hoogeboom Max Welling. "Argmax flows and multinomial diffusion: Towards non-autoregressive language models." NeurIPS 2021. [code1, code2] (image+text)

- Jacob Austin, Rianne van den Berg. "Structured denoising diffusion models in discrete state-spaces." NeurIPS 2021. [D3PM code] (image+text)

- AUTOREGRESSIVE DIFFUSION MODELS. ICLR 2022 

- Diffusion-LM Improves Controllable Text Generation

4. Speech

- Gautam Mittal, Ian Simon. "Symbolic music generation with diffusion models." ISMIR 2021.  (SMG)

- FastDiff: A Fast Conditional Diffusion Model for High-Quality Speech Synthesis 

- WaveGrad: Estimating Gradients for Waveform Generation. ICLR 2021 

5. text2img

- Chitwan Saharia. "Photorealistic Text-to-Image Diffusion Models with Deep Language Understanding". [non-official code]

- Aditya Ramesh, Mark Chen. "Hierarchical Text-Conditional Image Generation with CLIP Latents".  

- KNN-Diffusion: Image Generation via Large-Scale Retrieval 

### Compare Text Generation

1. AR vs NAR: 

- ARDM uses order-agnostic AR (parallelized)
NAR: multinomial diffusion, D3PM, SUNDAE, SMG, Diffusion-LM

2. Continuous vs discrete: 

- ARDM, D3PM, SUNDAE is discrete (clear transition)
Diffusion-LM is continuous, SMG first uses VAE to encode

3. Controllable: 

- Diffusion-LM uses plug and play
- WaveGrad uses condition with diffusion model
- CSDI: condition on input sequence