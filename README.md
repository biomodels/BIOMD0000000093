# BIOMD0000000093: Yamada2003_JAK_STAT_Pathway

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000093.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000093.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000093 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


_NCBS Curation Comments_ This model shows the control mechanism of Jak-Stat
pathway, here SOCS1 (Suppressor of cytokine signaling-I) was identified as the
negative regulator of Jak and STAT signal transduction pathway. Note: There
are a few ambiguities in the paper like initial concentration of IFN and some
reactions were missing in the paper that were employed for obtaining the
results. The graphs are almost similar to the graphs as shown in the paper but
still some ambiguities regarding the concentration are there. Thanks to Dr
Satoshi Yamada for clarifying some of those ambiguities and providing the
values used in simulations.

_Biomodels Curation Comments_ The model reproduces Fig 2 (A,C,E,G,I,K,M) of
the paper. The set of equations present in the paper are inadequate to
reproduce the figures mentioned . The model appears to have been fine tuned
after correspondence between the curators at NCBS and the authors. There is
however a slight discrepancy between the simulation results and the plots in
the paper. The model was tested on MathSBML.

This model originates from BioModels Database: A Database of Annotated
Published Models. It is copyright (c) 2005-2006 The BioModels Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html) .


