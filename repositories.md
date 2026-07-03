---
layout: page
title: Repositories
permalink: /repositories/
---

Selected public code. My full GitHub profile is
[@FranklinHu1](https://github.com/FranklinHu1).

## Projects

- **[NMRElucidator](https://github.com/MarklandGroup/NMRElucidator)** —
  official implementation of *"Pushing the limits of one-dimensional NMR
  spectroscopy for automated structure elucidation using artificial
  intelligence."* A transformer-based deep learning framework that performs
  de novo structure elucidation — predicting a molecule's formula and
  connectivity from only its 1D <sup>1</sup>H/<sup>13</sup>C NMR spectra — for
  systems of up to 40 non-hydrogen atoms, and is extensible to experimental
  data via fine-tuning. *(Python)*

- **[NMR2Struct](https://github.com/MarklandGroup/NMR2Struct)** —
  official implementation of *"Accurate and efficient structure elucidation
  from routine one-dimensional NMR spectra using multitask machine learning"*
  (ACS Central Science). A multitask model pairing a convolutional network with
  a transformer to predict molecular structure directly from 1D
  <sup>1</sup>H/<sup>13</sup>C NMR spectra, identifying the exact molecule
  69.6% of the time within its first 15 predictions. *(Python)*

- **[idiom](https://github.com/rotskoff-group/idiom)** —
  official repository for IDiom, a 122M-parameter autoregressive transformer
  trained on 37M intrinsically disordered protein regions from the AlphaFold
  Database. It generates intrinsically disordered proteins and regions
  (optionally conditioned on flanking context) and can be post-trained with
  reinforcement learning to optimize custom reward functions. *(Python)*

- **[chem-era](https://github.com/rotskoff-group/chem-era)** —
  official implementation of Energy Rank Alignment (ERA), a preference-based
  optimization method for searching chemical space at scale. ERA uses an
  explicit reward function to align autoregressive molecular generators,
  converging to a Gibbs–Boltzmann distribution without reinforcement learning,
  and is used to steer molecular transformers toward specified properties.
  *(Python)*

- **[DFTBML](https://github.com/djyaron/DFTBML)** —
  a machine-learned Density Functional-based Tight Binding (DFTB) model for the
  deep learning of chemical Hamiltonians. Rather than fitting the potential
  energy surface directly, DFTBML learns the underlying DFTB Hamiltonian
  parameters by training to *ab initio* data, yielding a semiempirical method
  that is data-efficient, low-cost, accurate, and interpretable. *(Python)*
