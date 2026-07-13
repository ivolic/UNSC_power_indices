# UN Security Council Power Indices

This repository contains the Python code used in:

Ilinca Drondoe and Ismar Volić, "Power Distribution in the United
Nations Security Council: A Comparative Analysis of Reform Proposals."

The Jupyter notebook `UNSC_power_indices.ipynb` calculates normalized
Banzhaf and Shapley-Shubik indices for the current UN Security Council
and the reform proposals considered in the paper.

The weighted voting games are calculated exactly using dynamic
programming rather than Monte Carlo simulation. The Weak Veto proposal
is calculated separately as a simple voting game in which a coalition
wins when it contains at least nine members, including at least four
permanent members.

## Requirements

- Python 3
- pandas

## Instructions

Open `UNSC_power_indices.ipynb` in JupyterLab and select:

Kernel → Restart Kernel and Run All Cells
