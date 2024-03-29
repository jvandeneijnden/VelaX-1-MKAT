[![DOI](https://zenodo.org/badge/402729652.svg)](https://zenodo.org/doi/10.5281/zenodo.10038516)

# Analysis reproduction repository for the MeerKAT discovery paper of radio emission from the Vela X-1 bow shock.

![Vela X-1 field with MeerKAT](Figure1_2/field.png?raw=true "Vela X-1 field with MeerKAT")

## Based on Van den Eijnden et al. (2021), MNRAS accepted. 
The full paper can be found on https://arxiv.org/abs/2111.10159 (open access).

This repository contains a Jupyter notebook and all required underlying data to produce the images in the paper "MeerKAT discovery of radio emission from the Vela X-1 bow shock". In order to run the Notebook, check the software requirements below, clone the repository, and run through each cell. The derivations and motivations for the performed calculations are also included to certain extend, although we refer to the main paper for full details. 

Please get in touch via email (jakob.vandeneijnden [at] st-hildas.ox.ac.uk) or github with questions. 

If this repository is useful for your own research, in addition to citing the original paper, please consider including a note to this repository as well.

## Software requirements

This notebook is written in Python2.7; updates to Python3.x should be straightforward but are left to the user.

In addition, this notebook makes use of the following packages, where the associated versions were used in the paper calculations. 

- numpy v1.15.4
- matplotlib v2.2.3
- aplpy v1.1.1
- scipy v1.1.0
- astropy v2.0.9

Finally, as noted in the notebook, Figure 3 of the paper is created using ds9 instead of python!
