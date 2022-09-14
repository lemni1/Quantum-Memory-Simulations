# Quantum-Memory-Simulations
XMDS2 simulations for modelling gradient echo memory 

This repository hosts the XMDS2 code for simulation gradient echo memory and cross phase modulation performed on gradient echo memory.  Included with the base XMDS2 code are jupyter notebooks that make it convenient for executing the code and visualizing the output.  The most reliable way run these simulations is by building a container from the DockerFile in the zip file.  You would need to then install the necessary python libraries such as jupyter notebook into the built container to run the execution and visualization notebooks.    

Otherwise, you can set up your own system to be able to run these simulations:
As XMDS2 runs natively in Linux and Mac OS, just initiate the kernel for this notebook as usual via anaconda or your own python installation.  For Windows users, you can execute your XMDS2 code in either a virtual box or using a Linux bash shell such as Bash on Ubuntu on Windows.  Just make sure you initiate your notebook kernel in the same environment so it can run the XMDS executable.  As for running the jupyter notebooks, it is recommended to set up a python virtual environment at the directory with the XMDS code and install all the relevant libraries in it.  Instructions: https://janakiev.com/blog/jupyter-virtual-envs/


