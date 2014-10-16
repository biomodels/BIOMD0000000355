# BIOMD0000000355: Abell2011_CalciumSignaling_WithAdaptation

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000355.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000355.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000355 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This model is from the article:  
**Parallel adaptive feedback enhances reliability of the Ca2+ signaling system.**   
Abell E, Ahrends R, Bandara S, Park BO, Teruel MN. _Proc Natl Acad Sci U S A._
2011 Aug 15. [21844332](http://www.ncbi.nlm.nih.gov/pubmed/21844332) ,  
**Abstract:**   
Despite large cell-to-cell variations in the concentrations of individual
signaling proteins, cells transmit signals correctly. This phenomenon raises
the question of what signaling systems do to prevent a predicted high failure
rate. Here we combine quantitative modeling, RNA interference, and targeted
selective reaction monitoring (SRM) mass spectrometry, and we show for the
ubiquitous and fundamental calcium signaling system that cells monitor
cytosolic and endoplasmic reticulum (ER) Ca(2+) levels and adjust in parallel
the concentrations of the store-operated Ca(2+) influx mediator stromal
interaction molecule (STIM), the plasma membrane Ca(2+) pump plasma membrane
Ca-ATPase (PMCA), and the ER Ca(2+) pump sarco/ER Ca(2+)-ATPase (SERCA). Model
calculations show that this combined parallel regulation in protein expression
levels effectively stabilizes basal cytosolic and ER Ca(2+) levels and
preserves receptor signaling. Our results demonstrate that, rather than
directly controlling the relative level of signaling proteins in a forward
regulation strategy, cells prevent transmission failure by sensing the state
of the signaling pathway and using multiple parallel adaptive feedbacks.

**Note:**

There are two models described in the paper to simulate basal and receptor
stimulated Ca 2+ signaling. 1) No adaptive feedback (MODEL1108050000) and 2)
with three slow adaptive feedback loops (this model: MODEL1108050001).


