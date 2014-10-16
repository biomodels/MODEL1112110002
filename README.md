# MODEL1112110002: Farhy2009_GlucagonCounterRegulationModel

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1112110002.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1112110002.git@20140916`

## Usage

Importing the model package.

`import MODEL1112110002 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**Pancreatic network control of glucagon secretion and counterregulation.**   
Farhy LS, McCall AL. _Methods Enzymol._ 2009;467:547-81.
[19897107](http://www.ncbi.nlm.nih.gov/pubmed/19897107) ,  
**Abstract:**   
Glucagon counterregulation (GCR) is a key protection against hypoglycemia
compromised in insulinopenic diabetes by an unknown mechanism. In this work,
we present an interdisciplinary approach to the analysis of the GCR control
mechanisms. Our results indicate that a pancreatic network which unifies a few
explicit interactions between the major islet peptides and blood glucose (BG)
can replicate the normal GCR axis and explain its impairment in diabetes. A
key and novel component of this network is an alpha-cell auto-feedback, which
drives glucagon pulsatility and mediates triggering of pulsatile GCR by
hypoglycemia via a switch-off of the beta-cell suppression of the alpha-cells.
We have performed simulations based on our models of the endocrine pancreas
which explain the in vivo GCR response to hypoglycemia of the normal pancreas
and the enhancement of defective pulsatile GCR in beta-cell deficiency by
switch-off of intrapancreatic alpha-cell suppressing signals. The models also
predicted that reduced insulin secretion decreases and delays the GCR. In
conclusion, based on experimental data we have developed and validated a model
of the normal GCR control mechanisms and their dysregulation in insulin
deficient diabetes. One advantage of this construct is that all model
components are clinically measurable, thereby permitting its transfer,
validation, and application to the study of the GCR abnormalities of the human
endocrine pancreas in vivo.

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not..  
  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


