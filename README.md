# README for Initial Conditions Notebook

## Overview

This repository contains a Jupyter notebook titled `InitialConditions.ipynb`, designed to generate initial conditions for scalar fields (in the form of csv files) that can be used in lattice simulations of preheating. This notebook implements procedures described in the excerpt from "The Art of Simulating the Early Universe – Part I" (arXiv: 2006.15122) and is directly applied in the research presented in the paper "Oscillon formation during inflationary preheating with general relativity" (arXiv: 2304.01673).

## Background

The study of preheating, the phase immediately following cosmic inflation in the early universe, is crucial for understanding the universe's history. Accurately generating initial conditions is essential for effectively simulating the non-linear dynamics that arise during this phase. The `InitialConditions.ipynb` notebook facilitates this by setting up a spectrum of fluctuations in the scalar field on a lattice. This method ensures that the simulations start with a distribution of fluctuations closely approximating real expected scenarios, as detailed in the methodology section of the referenced paper. This foundational step is vital for any subsequent analysis and interpretation of how preheating phenomena might unfold in the early universe.

## Implementation

The `InitialConditions.ipynb` notebook utilizes Python and standard scientific libraries to calculate and output the initial scalar field configurations (in 1D, 2D and 3D) necessary for starting lattice simulations. Details about the implementation can be read in the references below.

## Key References

- The Art of Simulating the Early Universe – Part I; Daniel G. Figueroa (IFIC, University of Valencia), Adrien Florio (Stony Brook University), Francisco Torrenti (University of Basel), Wessel Valkenburg (EPFL); arXiv: 2006.15122
- Oscillon formation during inflationary preheating with general relativity; Josu C. Aurrekoetxea (University of Oxford), Katy Clough (Queen Mary University), Francesco Muia (University of Cambridge); arXiv: 2304.01673

## Usage

To use this notebook:
1. Ensure that your Python environment includes packages like NumPy, SciPy, and Matplotlib.
2. Adjust parameters or to extend the types of initial conditions generated as required by different lattice simulations (see references below for the specifics).
3. Follow the step-by-step instructions within the notebook to generate the data.
