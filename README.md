# migraR
R package for migration analysis focused now on the Rogers and Castro multi exponential model and the estimation of the parameters using a bayesian simulation based on uniform a priori distributions for each parameter between 0 and 1. 


This package was created by J. Sebastian Ruiz-Santacruz and Jackson Garcés in 2018.

To install the package in R, you must install first the package dplyr and devtools running the following statements:

`install.packages(dplyr)`

`install.packages(devtools)`

and call them with `library(dplyr)` and `library(devtools)'

after running previous lines, you should use the function install.github to dowload de package as follows:

`install_github("elflacosebas/migraR")`

**Description**

The migraR package provides functions for estimate the parameters for Rogers and Castro Models: 
rc.7, rc.11, rc.13 are created in the example using the Migramodel class. You may create your own multiexponetial model making 
profit of the fucntion migramodel.

**migraR functions**

The migraR functions were concived for estimate via linear optimization of the log(Migration Rate), the parameters of 
the Rogers and Castro models wit seven, eleven and thirteen parameters. Besides, the package 
gives the user the posibility to investigate wich curve fits better using the methodology provided 
in the IUSSP manual for the estimation of Rogers and Castro multi exponential model migration 
schedule with variation on the optimization method.

http://demographicestimation.iussp.org/content/multi-exponential-model-migration-schedule


Package under contiuous changes! place your bugs on the github tab issues :) :rocket:
