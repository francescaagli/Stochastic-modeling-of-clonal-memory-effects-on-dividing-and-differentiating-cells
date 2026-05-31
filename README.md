# Stochastic modeling of clonal memory effects on dividing and differentiating cells

## Project description
Clonal memory is defined as the inheritance of cellular properties across multiple cell generations and it has been observed in several biological systems. In particular, cells sharing a common ancestor showed this memory by dividing synchronously over multiple divisions. This finding raises questions about how such memory influences changes in population size and the composition of clonal families that create a healthy hematopoietic compartment. Here, we developed a stochastic simulation of dividing cells under two different conditions: with and without clonal memory. Our results revealed that clonal memory increased variability in the population size and heterogeneity between clonal family sizes, but did not affect average population growth or the rate of differentiation. These effects became more evident for larger populations in a fashion dependent on the ratio between the initial number of clones and the final population size, suggesting that our findings may generalize to larger real-scale systems. The simulation therefore suggests that clonal memory enhances variability in cellular responses and helps maintain the diversity of cell progenitors and cell type necessary for healthy development under different division rates such as homeostasis and post-inflammation recovery.

## Repository structure

The repository is organized into three main folders:

### 1. division times distribution
This folder contains experimental data of cell division from *Donada et al. (2025)*, together with their analysis to obtain the log-normal distribution parameters used in the simulations:
- `Merged_bone_marrow.xlsx` – Experimental division times measured in bone marrow.
- `Merged_cord_blood.xlsx` – Experimental division times measured in cord blood.
- `lognormal_fit.ipynb` – Jupyter notebook with experimental data fits.
- `lognormal_fit.html` – HTML version of the notebook.

### 2. memory
This folder contains the Python code used to simulate and analyse the system in the **presence clonal memory**:
- `simulations_with_memory.ipynb` – Jupyter notebook.
- `simulations_with_memory.html` – HTML version of the notebook.

### 3. no memory
This folder contains the Python code used to simulate and analyse the system in the **absence of clonal memory**:
- `simulations_without_memory.ipynb` – Jupyter notebook.
- `simulations_without_memory.html` – HTML version of the notebook.
