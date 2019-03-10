PyTorch Tutorial
================================================================================

This repository contains material to get started with
[PyTorch](https://pytorch.org/) v1.0.

<hr>

Table of Contents
--------------------------------------------------------------------------------

### 0. Foreword
- [Foreword](notebooks/00_index.ipynb) - Why PyTorch and why not?

### 1. Basics
- TODO

### 2. Computer Vision
- TODO Transfer Learning

### X. Misc
- TODO

<hr>


Setup
--------------------------------------------------------------------------------

### Requirements

- Python 3.6 or higher
- conda

### Install Dependencies

```bash
# If you have a GPU and CUDA 10
conda env create -f environment_gpu.yml
# If you don't have a GPU
conda env create -f environment_cpu.yml

# activate the conda environment
source activate pytorch_tutorial_123
```

### Download data and models

Download data and models for the tutorial:

```bash
python download_data.py
```

Then you should be ready to go.
Start jupyter lab

```bash
jupyter lab
```


Misc
--------------------------------------------------------------------------------

To get the [Table of Contents](https://github.com/ian-r-rose/jupyterlab-toc)
displayed within jupyter lab do the following:
```bash
# install node
conda install -c conda-forge nodejs
# install the toc extension
jupyter labextension install jupyterlab-toc
```

Prior Versions
--------------------------------------------------------------------------------

- Version of this tutorial for the PyData 2018 conference
  [material](https://github.com/sotte/pytorch_tutorial/tree/pydata2018)
  [video](https://nodata.science/pydata-pytorch-tutorial.html)
