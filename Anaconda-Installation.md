# Anaconda Installation
Anaconda is a powerful tool that allows users to setup individual environments for different software and data science projects. These indvidual envrionments allow for different software packages with different versions to exist without interfering with one another. To begin, the software can be downloaded from [Anaconda](https://www.anaconda.com/). With this softwrare installed, the shell can be launched and a new environment can be created with 

```
conda create -n cse620b python=3.7
```

This environment can now be accessed with 

```
conda activate cse620b
```
With the environment now created and activated, software packages can be installed. First, conda-forge is installed which is a recommendation from class and helped with issues installing rasterio. Conda-forge can be activated using the following commands.
```
conda config --add channels conda-forge
conda config --set channel_priority strict
conda install <package-name>
```

## Install JupyterLab
With conda-forge installed, JupyterLab can now be installed and launched. Jupyterlab allows users to activate different kernels and interact with the terminal from a clean browser window. JupyterLab is installed and launched with the following commands.
```
conda install jupyterlab
jupyter lab
```

## Import Packages

## Package Check
