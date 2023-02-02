# SIGIRAgglomerativeClusteringPSS

This repository contains the code and link to the data used in the paper "Using Deep Learned Vector Representations for Page Stream Segmentation by Agglomerative Clustering", submitted to the Short Paper Track of SIGIR 2023.

## Installation

To run the experiments presented in this research, we recommend using `Aconda` to install the dependencies required, and we have included a .yml file to easily install all the required dependencies. Although we recommend the usage of `conda` we have also included a `requirements.txt` file, so the required dependencies can also be installed using  `pip`.

Below are the steps for installing the required dependencies:

- Step 1: Clone /Download the repository to your local computer, for example by using the command below: ``

- Step 2 :Unzip the directory if needed, and change into the directory in the terminal, for example `cd path/to/folder/elm `

- Step 3: If you are using conda, you can use the command below to create a new conda environment with all the requirements you need to run the code in this repository.

`conda env create -f environment.yml`

This will create an environment called 'ELM_IRJ_paper_env', which can be used to run the experiments in this notebook. Note that this environment comes with `jupyter lab` already installed, but without a link to the evironment, so you can't select it in Jupyter Lab yet.
To do this, first activate the environment:

`conda activate ELM_IRJ_paper_env`

Then run the following command:

`ipython kernel install --name "ELM_IRJ_experiments_kernel" --user`

Now the kernel is linked to Jupyter Lab, and you can select it as the kernal to run the notebooks in Jupyter Lab. to start Jupyter Lab, make sure the environment is activated and type `jupyter lab` in the terminal.


1. Installation using Anaconda
  - To install using Anaconda, simply run `ADD COMMAND`

2. Installation using pip
  - To install using pip, simply run `ADD COMMAND`
  
  
## Contents

## Dataset

The dataset used in this research is available through Zenodo () as an anonymous data entry. The instructions for downloading the data are pretty straightforward, but we have also included a script in this repository that will allow you to automatically download the data as part of the set up of the repository.
