# FEMclasses

## Installation

Install Anaconda (for windows systems) or miniconda (for linux/Mac systems) from https://www.anaconda.com/
Make sure you use Python version 3.7 or higher

## Installation of required packages

### FEM : virtual env

conda create -n FEM
conda activate FEM

### Installing packages in the virtual env

conda install -n FEM numpy matplotlib jupyter

### Change jupyter default directory

In an anaconda prompt (or terminal for Mac/Linux), type : 

```
jupyter notebook --generate-config
```

Edit the configuration file, search **c.NotebookApp.notebook_dir** and modify it, like :
```
c.NotebookApp.notebook_dir = 'F:/FEMclasses'
```

### Launch jupyter notebook

In an anaconda prompt (or terminal for Mac/Linux), type : 
```
jupyter notebook
```
