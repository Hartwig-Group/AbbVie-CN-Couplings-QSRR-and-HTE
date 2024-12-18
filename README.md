# Overview 

This repository includes all code associated with the with the paper "Carboxylate Salts Soluble in Organic Solvents Significantly Expands the Substrate Scope for Pd-catalyzed C-N Cross-Coupling Reactions" and instructions for reproducibility.

Paper: 

Zenodo (including DFT calculations and structures): 

## Project

The code for this project is broken into two main sections: `ligand-qsar` which is focused on the chemoinformatic investigation of ligand activity and yields; and and the other for substrate clustering and selection for HTE.

## Installation

This repository uses [uv](https://github.com/astral-sh/uv) to manage and install the dependencies. To install the dependencies, install uv and run the following command:

```bash
$ git clone git@github.com:Hartwig-Group/Abbvie-CN-Couplings.git
$ cd Abbvie-CN-Couplings
$ uv sync
```

Then to run any code, run then using the virtual environment created by uv:

```bash
$ uv run python my_script.py
```

## Repository Structure

```
abbvie-cn-couplings/
|-- data/
|   |-- ligand-qsar/
|-- notebooks/
|   |-- ligand-qsar/
|   |  |-- nh-bivariate-thresholding.ipynb
|   |  |-- ... 
|-- pyproject.toml
|-- uv.lock
|-- README.md
```
The "abbvie-cn-couplings" project is organized into several key directories, each serving a distinct purpose. Below is an overview of the main components:

**1. data/**
   - Folder for datasets and other relevant data files used in the project. This is broken into two folders, one for the ligand-qsar and the other for substrate clustering.
   
**2. notebooks/ligand-qsar/**
   - Jupyter notebooks associated with the qsar modeling of ligand activity and yields.
     
**3. notebooks/substrate-clustering/**
  - Jupyter notebooks associated substrate clustering and selection.

**4. pyproject.toml**
   - TOML file specifying the project's dependencies and environment configuration, facilitating reproducibility.

**5. uv.lock**
   - UV lock file to ensure reproducibility in environment creation.

**6. README.md**
   - The project's main documentation providing a high-level overview, usage instructions, and any other essential information for collaborators and users.

## Citation 

