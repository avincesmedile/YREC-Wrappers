# YREC-Wrappers
Wrappers, helpful codes, and additional machinery to interface with YREC in languages such as Python. Presented here as individual scripts to copy/paste and/or download. Compatible with command line and Jupyter/Spyder, and other such programs. We provide the '''modelgrid_tools''' folder for the primary mode of interacting with the grid. The '''modelgrid_tools_legacy''' is the precursor to the modelgrid_tools code, and is also applicable. The '''_legacy''' tools are more Jupyter Notebook (or another Python interface/environment) focused, whereas the primary '''_tools''' are a combination of an app/web compiler for Python and command line prompts. The main tools folder also provides compatibility with '''hypergator''' and '''slurm'''. 

## modelgrid_tools:
Contains guidelines and tools to create a grid of models in YREC. See the readme.md file in the folder for more details. This also contains update_nml.py, which allows the user to change several namelist parameters for multiple nml files at once.

## modelgrid_tools_legacy: 
Precursor for tools. Alternative scripts in the event modelgrid_tools do not work. Contains namelist updaters, file readers, and a parallel processing batch runner function for running large numbers of YREC tools without the use of an external server or parallel processing network.


