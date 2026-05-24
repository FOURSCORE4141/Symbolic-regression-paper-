# Symbolic-regression-paper-
Enhancing Symbolic Regression with Interpolation-Based Super-Resolution Sampling: Applications to Exponential and Quantum Systems

This repository contains the paper, figures, and reproducibility materials for a project on improving symbolic regression through interpolation-based upsampling.

## Overview

Symbolic regression is a method for discovering analytical expressions from data.  
This project investigates whether interpolation-based super-resolution can improve symbolic regression performance on sparse and noisy datasets.

Two benchmark systems are studied:

- The exponential function.
- The ground-state wavefunction of the quantum harmonic oscillator.

The main idea is simple: if the input data are denser and smoother, symbolic regression can recover the underlying equation more accurately.

## Main Results

The project compares two pipelines:

1. Direct symbolic regression on low-resolution data.
2. Interpolation-based upsampling followed by symbolic regression.

The upsampled pipeline shows lower reconstruction error and better recovery of the analytical expressions.

## Why This Project Matters

This work is useful because it explores how data resolution affects symbolic regression performance.  
It also connects scientific machine learning with preprocessing ideas from interpolation and signal enhancement.

## Repository Contents

- `paper/`  
  Final paper PDF and LaTeX source.

- `figures/`  
  Figures used in the paper.

- `code/`  
  Notebook or scripts used for dataset generation, interpolation, and symbolic regression.

- `data/`  
  Optional generated datasets or exported results.

## How to Reproduce

1. Install the required Python packages.
2. Generate the synthetic datasets.
3. Apply interpolation-based upsampling.
4. Run symbolic regression using PySR.
5. Compare the low-resolution and upsampled results.


- The current version focuses on synthetic benchmark systems.
- The repository is intended to support reproducibility and community feedback.
- Future versions may include broader benchmarks and additional ablation studies.

## Author

Khadija Tuj Zohora Dina  
Independent Researcher  
Dhaka, Bangladesh  
Email: fourscore4141@gmail.com
