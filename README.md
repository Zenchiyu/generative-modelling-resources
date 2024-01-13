# Generative Modelling resources

This repository contains (top notch) useful resources for image or video generation. We use "score-based generative models" interchangeably with "diffusion models".

## Videos
- [Diffusion and Score-Based Generative Models | Yang Song](https://youtu.be/wMmqCMwuM2Q); explains many key papers including
    - [Generative Modeling by Estimating Gradients of the Data Distribution](https://arxiv.org/abs/1907.05600)
    - [Score-Based Generative Modeling through Stochastic Differential Equations](https://arxiv.org/abs/2011.13456)
- [Elucidating the Design Space of Diffusion-Based Generative Models | Miika Aittala](https://youtu.be/T0Qxzf0eaio); explains at the intuitive level their paper and most importantly, how they make the "flow lines" more straight for faster sampling speed (easier for Euler method).
- [Flow Matching: Simplifying and Generalizing Diffusion Models | Yaron Lipman](https://youtu.be/5ZSwYogAxYg); explains where diffusion models situate compared to flow-based models (or more specifically continuous normalizing flows)

## Websites
- [What are Diffusion Models?](https://lilianweng.github.io/posts/2021-07-11-diffusion-models/)
- [Generative Modeling by Estimating Gradients of the Data Distribution](https://yang-song.net/blog/2021/score/)
- [Flow-based Deep Generative Models](https://lilianweng.github.io/posts/2018-10-13-flow-models/); explains "discrete-time normalizing flows"

## Papers
- [Generative Modeling by Estimating Gradients of the Data Distribution](https://arxiv.org/abs/1907.05600)
- [Denoising Diffusion Probabilistic Models](https://arxiv.org/abs/2006.11239); connects for the first time diffusion probabilistic models and denoising score matching with Langevin dynamics
- [Score-Based Generative Modeling through Stochastic Differential Equations](https://arxiv.org/abs/2011.13456); formalizes the link between DDPM and SMLD by introducing predictor-corrector samplers and merge them under score-based generative models.
- [Neural Ordinary Differential Equations](https://arxiv.org/abs/1806.07366); the basis for the relation between CNFs and score-based generative models (a.k.a. diffusion models)
- [Flow Matching for Generative Modeling](https://arxiv.org/pdf/1806.07366.pdf)
