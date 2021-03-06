# BIOMD0000000545: MODEL1407230000

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000545.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000545.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000545 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


Ouyang2014 - photomorphogenic UV-B signalling network

This model is described in the article:

[Coordinated photomorphogenic UV-B signaling network captured by mathematical
modeling.](http://identifiers.org/pubmed/25049395)

Ouyang X, Huang X, Jin X, Chen Z, Yang P, Ge H, Li S, Deng XW.

Proc. Natl. Acad. Sci. U.S.A. 2014 Aug; 111(31): 11539-11544

Abstract:

Long-wavelength and low-fluence UV-B light is an informational signal known to
induce photomorphogenic development in plants. Using the model plant
Arabidopsis thaliana, a variety of factors involved in UV-B-specific signaling
have been experimentally characterized over the past decade, including the
UV-B light receptor UV resistance locus 8; the positive regulators
constitutive photomorphogenesis 1 and elongated hypocotyl 5; and the negative
regulators cullin4, repressor of UV-B photomorphogenesis 1 (RUP1), and RUP2.
Individual genetic and molecular studies have revealed that these proteins
function in either positive or negative regulatory capacities for the
sufficient and balanced transduction of photomorphogenic UV-B signal. Less is
known, however, regarding how these signaling events are systematically
linked. In our study, we use a systems biology approach to investigate the
dynamic behaviors and correlations of multiple signaling components involved
in Arabidopsis UV-B-induced photomorphogenesis. We define a mathematical
representation of photomorphogenic UV-B signaling at a temporal scale.
Supplemented with experimental validation, our computational modeling
demonstrates the functional interaction that occurs among different protein
complexes in early and prolonged response to photomorphogenic UV-B.

This model is hosted on [BioModels Database](http://www.ebi.ac.uk/biomodels/)
and identified by:
[BIOMD0000000545](http://identifiers.org/biomodels.db/BIOMD0000000545).

To cite BioModels Database, please use: [BioModels Database: An enhanced,
curated and annotated resource for published quantitative kinetic
models](http://identifiers.org/pubmed/20587024).

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.


