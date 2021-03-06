# Likelihood-free MCMC with Approximate Likelihood Ratios
Official repository for the [paper](https://joerihermans.com/papers/lfmcmc.pdf) "Likelihood-free Markov chain Monte Carlo with Approximate Likelihood Ratios".

The code relies heavily on [hypothesis](https://github.com/montefiore-ai/hypothesis), which is a small framework to tackle likelihood-free inference.

## Abstract
> We propose a novel approach for posterior sampling with intractable likelihoods. This is an increasingly important problem in scientific applications where models are implemented as sophisticated computer simulations. As a result, tractable densities are not available, which forces practitioners to rely on approximations during inference. We address the intractability of densities by training a parameterized classifier whose output is used to approximate likelihood ratios between arbitrary model parameters. In turn, we are able to draw posterior samples by plugging this approximator into common Markov chain Monte Carlo samplers such as Metropolis-Hastings and Hamiltonian Monte Carlo. We demonstrate the proposed technique by fitting the generating parameters of implicit models, ranging from a linear probabilistic model to settings in high energy physics with high-dimensional observations. Finally, we discuss several diagnostics to assess the quality of the posterior.
---

## Presentation
A presentation summarizing this work can be found in the `talk/` directory or can be viewed [online](https://joerihermans.com/talks/lfmcmc/).

---

## Source code

> TODO
---

## Notebooks

> TODO
---

## Citing
```bibtex
@article{}
```
---
