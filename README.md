# Figure Code for Springer Manuscript

This repository contains the Python code used to generate the numerical figures accompanying the manuscript on sharp bounds for the loss tangent of a generalized Maxwell solid under partial relaxation-spectrum information.

## Author

Eesha Iyer

## Contents

The main notebook is:

- `Springer_Figures.ipynb`

The notebook generates the following figures:

1. Response geometry and feasible response region
2. Global optimality certificates
3. Extremal relaxation spectra
4. Sharp loss-tangent bounds
5. Optimizer transitions with frequency
6. Low- and high-frequency asymptotic checks

## Running the Code

The notebook was developed in Google Colab and can be run directly in a Colab environment.

To reproduce the figures:

1. Open `Springer_Figures.ipynb` in Google Colab.
2. Run the cells sequentially from top to bottom.
3. The required Python packages are installed automatically by the first code cell.
4. Generated figures are saved in the directory:

   `maxwell_figures_output/`

Each figure is saved in both PNG and SVG format.

## Dependencies

Notebook uses:

- Python 3
- NumPy
- SciPy
- Matplotlib
- SymPy
- CVXPY
- Clarabel
- Pillow

## Parameters

The numerical examples use illustrative dimensionless parameters chosen to demonstrate the theoretical results. They are NOT experimental measurements of a particular material.


A permanent archived version of this repository is available through Zenodo:

**DOI:** 
