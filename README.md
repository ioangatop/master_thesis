# Master Thesis: "Self-Supervised Variational AutoEncoders"

### _Abstract_

In this thesis, we present a novel class of generative models, called _Self-Supervised Variational Auto-Encoder_ (selfVAE), where we improve plain architecture (VAE) through self-supervised representations. The proposed method is able to perform both conditional and unconditional sampling, while demonstrating improved performance in sample synthesis and density estimation on standard image modelling benchmarks. Starting with the special case, where we use a single self-supervised transformation as a latent variable, we generalize to a multi-levelled architecture, which is agnostic to the provided representations. We show that the benefits of employing a multi-levelled self-supervised framework against the Variational Auto-Encoder (VAE) is more obvious when we move to higher-dimensional data, where the second fails to scale efficiently. Furthermore, we examine the advantages of choosing suitable representations for the data at hand when we want to focus on specific characteristics, which indicates a notion of introducing prior knowledge to the data generation process, but also allows for additional functionalities. The flexibility of ssVAE in data reconstruction through multiple ways find a particularly interesting use case in data compression tasks, where we can trade-off more memory for better data quality, and vice-versa. Additionally, we suggest replacing the fixed latent prior with a data-driven bijective network, as it allows the model to reach better likelihood estimations and impressive generations.

### _Figures_

<p align="center">
  <img src="images/generations.png" width="900"/>
</p>


<p align="center">
  <img src="images/compressions.png" width="900"/>
</p>

<p align="center">
  <img src="images/model.png" width="900"/>
</p>


### _Author_
Ioannis Gatopoulos, 2020

