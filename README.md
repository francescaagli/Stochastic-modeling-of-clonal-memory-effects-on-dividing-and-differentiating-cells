# Stochastic modeling of clonal memory effects on dividing and differentiating cells

## Project description
Clonal memory is defined as the phenomenon responsible for the inheritance of cellular properties across multiple cell generations and it has been observed in several biological systems. In particular, human hematopoietic stem and progenitor cells sharing a common ancestor showed this memory by dividing synchronously over multiple divisions. This finding raised questions about how such memory influenced population dynamics and clonal families composition. Here, we developed a stochastic simulation of dividing and differentiating cells under two different conditions: with and without clonal memory. Our results revealed that clonal memory did not affect the differentiation process or average population growth, but it increased variability in the population size and heterogeneity between clonal family sizes. These effects became more evident for larger populations and could therefore be generalized to real-scale systems.

## Repository structure

The repository is organized into three main folders:

### 1. division times distribution
This folder contains experimental data of cell division from *Donada et al. (2025)*, together with their analysis to obtain the lognormal distribution parameters used in the simulations:
- `bone_marrow_division_times.xlsx` – Experimental division times measured in bone marrow.
- `cord_blood_division_times.xlsx` – Experimental division times measured in cord blood.
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
