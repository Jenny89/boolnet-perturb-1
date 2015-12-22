# Robustness and Plasticity in Regulatory Networks

The BoolNetPerturb package adds functions to BoolNet for perturbing Boolean Regulatory Networks. This functions can be used for the study of biological systems. This package is capable of labeling states, simulating multiple knock-outs and over-expressions and simulating fixed and transient perturbations in the states and trajectory of a network. See the Jupyter Tutorials for more examples.

## Installation
Using [devtools](https://github.com/hadley/devtools) in R:
```
install.packages("devtools")
library(devtools)
install_github("mar-esther23/boolnet-perturb")
```

Download from github:

1. Download the `.zip` from [github](https://github.com/mar-esther23/boolnet-perturb). 

2. Unzip the file

3. In `terminal`: `R CMD INSTALL boolnet-perturb-master.zip`

4. Or in `R`: `install.packages(<path/to/boolnet-perturb>, repos = NULL, type="source")`


The ugly option (not recommended):

1. Download the [functions code](https://github.com/mar-esther23/boolnet-perturb/blob/master/BoolNetPerturb/R/BoolNetPerturb.R).

2. In `R`: `source("path/to/BoolNetPerturb.R")`




For running the tutorials you need [Jupyter](http://jupyter.readthedocs.org/en/latest/install.html) and the [Rkernel](http://irkernel.github.io/installation/).

## Jupyter Tutorials

* [Introduction](./Jupyter_Tutorial/RPRN-Introduction.ipynb)
    * Robustness in biological systems
    * Boolean regulatory networks
    * Biological system: Th17/iTreg network
* [BoolNet](./Jupyter_Tutorial/RPRN-BoolNet.ipynb)
    * Installation
    * Construction
    * Attractors
    * Labels
* [Functions](./Jupyter_Tutorial/RPRN-Functions.ipynb)
    * Over-expression and knock-outs
    * Fixed environments
    * Truth tables
* [Updating](./Jupyter_Tutorial/RPRN-Updating.ipynb)
    * Synchronous vs asynchronous
    * Transition table
* [States and trajectories](./Jupyter_Tutorial/RPRN-States-Trajectories.ipynb)
    * Transient perturbations
    * Stochastic noise
* [Appendix](./Jupyter_Tutorial/RPRN-Appendix.ipynb)
    * Simulation and model checking
    * Importing and exporting with SBML-qual

--------------------------------------------

<p align="right"> Do I dare </p>
<p align="right"> disturb the universe? </p>
<p align="right"> In a minute there is time </p>
<p align="right"> for decisions and revisions </p>
<p align="right"> which a minute will reverse. </p>
