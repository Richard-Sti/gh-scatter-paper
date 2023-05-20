# The scatter in the galaxy-halo connection: a machine learning analysis

LaTeX source repository for the article "[The scatter in the galaxy-halo connection: a machine learning analysis](https://arxiv.org/abs/2202.14006)". If you find any of this useful, please cite paper [1]. If you have any questions, please contact [me](mailto:richard.stiskalek@protonmail.com).


## Abstract

We apply machine learning, a powerful method for uncovering complex correlations in high-dimensional data, to the galaxy--halo connection of cosmological hydrodynamical simulations. The mapping between galaxy and halo variables is stochastic in the absence of perfect information, but conventional machine learning models are deterministic and hence cannot capture its intrinsic scatter. To overcome this limitation, we design an ensemble of neural networks with a Gaussian loss function that predict probability distributions, allowing us to model statistical uncertainties in the galaxy--halo connection as well as its best-fit trends. We extract a number of galaxy and halo variables from the Horizon-AGN and IllustrisTNG100-1 simulations and quantify the extent to which knowledge of some subset of one enables prediction of the other. This allows us to identify the key features of the galaxy--halo connection and investigate the origin of its scatter in various projections. We find that while halo properties beyond mass account for up to $50$ per cent of the scatter in the halo-to-stellar mass relation, the prediction of stellar half-mass radius or total gas mass is not substantially improved by adding further halo properties. We also use these results to investigate semi-analytic models for galaxy size in the two simulations, finding that assumptions relating galaxy size to halo size or spin are not successful.


## Reference
[1] Richard Stiskalek and others, The scatter in the galaxy–halo connection: a machine learning analysis, Monthly Notices of the Royal Astronomical Society, Volume 514, Issue 3, August 2022, Pages 4026–4045, https://doi.org/10.1093/mnras/stac1609
