# Variational Auto Encoder (VAE)

VAE is a way to perform efficient inference and learning in directed probabilistic models, in the presence of continuous latent variables with intractable posterior distributions, and large datasets? It introduces a stochastic variational inference and learning algorithm that scales to large datasets and, under some mild differentiability conditions, even works in the intractable case. This works contributions is two-fold. First, we show that a reparameterization of the variational lower bound yields a lower bound estimator that can be straightforwardly optimized using standard stochastic gradient methods. Second, we show that for i.i.d. datasets with continuous latent variables per datapoint, posterior inference can be made especially efficient by fitting an approximate inference model (also called a recognition model) to the intractable posterior using the proposed lower bound estimator. Theoretical advantages are reflected in experimental results.

![VAE Image](https://lilianweng.github.io/posts/2018-08-12-vae/autoencoder-architecture.png)


# Resutls
| Space | Changes in Time |
| :---  | :-------------- |
|sajjad|right|

![gif 1](https://github.com/SajjadPSavoji/Variational-Auto-Encoder/blob/master/vae_grid%20(4).gif)
![gif 2](https://github.com/SajjadPSavoji/Variational-Auto-Encoder/blob/master/vae_latent%20(7).gif)

# Resources
* [Publication](https://arxiv.org/abs/1312.6114)
* [Dataset](http://yann.lecun.com/exdb/mnist/)
