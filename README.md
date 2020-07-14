# SDSC HPC User Training:  Jupyter Notebook Examples 

This repository contains a few examples of Jupyter Notebooks that have been run & tested on Comet and other HPC systems at SDSC.

To run notebooks on SDSC HPC systems, we recommend that you run jupyter notebooks on Comet using the *secure* [SDSC Reverse Proxy Service (RPS)](https://comet-notebooks-101.readthedocs.io/en/comet/methods/reverseProxy.html). 

By default, Jupyter notebooks run over HTTP, which is not secure. RPS is a prototype system that will allow users to launch *secure* (HTTPS) Jupyter Services on on any Comet compute node using a simple bash script called start_notebook. The notebooks will be made available to the user outside of the cluster firewall using a secure *HTTPS* connection between the external users web browser and the reverse proxy server.

For information about running notebooks on SDSC HPC systems, see the tutorial 
[SDSC Notebooks 101](https://comet-notebooks-101.readthedocs.io/en/comet/index.html)
tutorial. 

This repo will be updated regularly with example notebooks, primarly for beginners and those who are new to using notebooks on Comet.
