# BIOMD0000000254: Bier2000_GlycolyticOscillation

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000254.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000254.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000254 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**How yeast cells synchronize their glycolytic oscillations: a perturbation analytic treatment**   
Bier M, Bakker BM, Westerhoff HV. _Biophys. J_ 2000 Mar;78(3):1087-93.
[10692299](http://www.ncbi.nlm.nih.gov/pubmed/10692299) ,  
**Abstract:**   
Of all the lifeforms that obtain their energy from glycolysis, yeast cells are
among the most basic. Under certain conditions the concentrations of the
glycolytic intermediates in yeast cells can oscillate. Individual yeast cells
in a suspension can synchronize their oscillations to get in phase with each
other. Although the glycolytic oscillations originate in the upper part of the
glycolytic chain, the signaling agent in this synchronization appears to be
acetaldehyde, a membrane-permeating metabolite at the bottom of the anaerobic
part of the glycolytic chain. Here we address the issue of how a metabolite
remote from the pacemaking origin of the oscillation may nevertheless control
the synchronization. We present a quantitative model for glycolytic
oscillations and their synchronization in terms of chemical kinetics. We show
that, in essence, the common acetaldehyde concentration can be modeled as a
small perturbation on the "pacemaker" whose effect on the period of the
oscillations of cells in the same suspension is indeed such that a
synchronization develops.


