# Multi-Omics Integration for Personalized Medicine Using MOFA

To run this tutorial, first set up micromamba on your computer using

`"${SHELL}" <(curl -L micro.mamba.pm/install.sh)`

`source ~/.bashrc` (Linux) or `source ~/.zshrc` (Mac)

Then, create a new environment with Python 3.11 using the commands

`micromamba create -n mofa -c conda-forge python==3.11`

`micromamba activate mofa`

Then, install the required packages using

`pip install plotnine decoupler scikit-learn seaborn jupyterlab ipykernel`

and install the mofaflex development version with

pip install `git+https://github.com/bioFAM/mofaflex.git@main`

Install the jupyter kernel:

`python -m ipykernel install --user --name mofa`,

then run jupyter lab:

`jupyter lab`.