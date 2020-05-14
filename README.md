# Files

There are two Jupyter Notebooks available: (i) An interactive simulation of the basic SUIR model for use with Google Colab. (ii) A fully documented Jupyter Notebooks, for use in Google Colab or JupyterLab, which includes a full derivation of the model, and numerous simulation studies. This notebook is the basis for the manuscript linked to this work. The main file is named "SUIR Modelling VXY.ipynb". The more basic notebook with the interactive SUIR model is named SUIR Modelling Interactive.ipynb"

V04 added the calculation of $R_t$ and a comparison of scenarious, strategies and policies w.r.t. the Area Under Curve (AUC) of a refence case.

# Abstract

During the SARS-CoV-2 pandemic, numerous mathematical models have been developed. Reporting artefacts and missing data about asymptomatic spreaders, imply considerable margins of uncertainty for model-based predictions. Epidemiological models can however also be used to investigate the consequences of measures to control the pandemic, reflected in changes to parameter values.

We present a SIR-based, SUIR model in which the influence of testing and a reduction of contacts is studied by distinguishing Unidentified' andIdentified' spreaders of infections. The model uses four ordinary differential equations and is kept deliberately simple to investigate general patterns occurring from testing and contact restrictions. The model goes beyond other efforts, by introducing time dependent parameter curves that represent different strategies in controlling the pandemic.
Our analysis reveals the effect of `pro-active' testing for the design of contact restriction measures. By pro-active testing we mean testing beyond those people who show symptoms. The simulations can explain why the timing of contract restrictions and pro-active testing is important. The model can also be used to study the consequence of different strategies to exit from lockdown.

Our SUIR model is implemented in Python and is made available through a Juypter Notebooks. This an extensive documentation of the derivation and implementation of the model, as well as transparent and reproducible simulation studies. Our model should contribute to a better understanding of the role of testing and contact restrictions.
