# Circuit-Simulator

:star:This repository is the end of year project of Imperial College EIE course in Year 1. The project is selected as the best Circuit Simulator Project (overall Runner-Up Award) among the cohort.

## Overview

Our circuit simulator is a C++ software package that performs DC and AC analysis for a given circuit. The circuit will be passed into the program in the form of a netlist (sample files listed in the <code>/test</code> folder). DC operation is performed first to find the DC operating point, which is then used to calculate parameters of non-linear devices. Then AC analysis is performed based on these parameters. It will find the transfer functions of selected nodes and output a netlist (<code>simdata.txt</code>) that contains the magnitude and phase of a transfer function under different frequencies. Then MATLAB is used to plot a magnitude-frequency graph and a phase-frequency graph.

## To run the code
The code can be executed by running the bash file: <code> ./run.sh </code>

Then, MATLAB code <code>plotsim.mat</code> is used to plot the output data (<code>simdata.txt</code>) on graphs.

## Directories
### doc
This folder contains the initial project specification, the final report for the project and a short explanation video.

### include
This folder contains all the header files.

### src
This folder contains all the cpp source code files.
