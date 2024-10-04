# MixSolvMD

This is a GROMACS tutorial for Mixed Solvent MD simulations

### Installation & requirements

The easiest ways to do this tutorial is to clone the repository using git clone or to download the zip file and extract the repository.

This tutorial requires:
  - Jupyter Notebook or JupyterLab to open the notebook.
  - GROMACS (version from at least 2022)
  - The following Python packages: py3Dmol, RDKit, NumPy, pandas, seaborn, matplotlib, MolParse (from https://github.com/mwinokan/MolParse) and MD_tools (from https://github.com/cvallee/MD_Tools)

### Basic tutorial

To follow the basic tutorial please follow the instruction from the notebook "GmxMixSolvMD.ipynb".
All the files needed to run the simulations are provided in the "input/" directory. If you don't have access to GROMACS or to any HPC for the simulations, expected outputs are available in the "output/" directory. The notebook should work by simply clicking on "Restart the kernel and run all cells". If you decide to run the simulation yourself from the same input files, you will probably get slightly different results due to the randomness of some steps.

### Going a little bit further

If you would like to perform extra analyses from the Mixed Solvent MD simulations, please follow the instructions from the notebook "GmxMixSolvMD_extra.ipynb".
This notebook only shows some example or analyses that can be done from the simulations, but other analyses are also possible.
