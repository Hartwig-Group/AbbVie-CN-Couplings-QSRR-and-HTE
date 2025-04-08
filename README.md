# Overview 

This repository includes all code associated with the with the paper _**"Unleashing the Power of Potassium 2-Ethylhexanoate as a Mild and Soluble Base for Pd-catalyzed C-N Cross-Coupling"**_ and instructions for reproducibility.

Paper: 

Zenodo Archive: 

## Project

The code for this project is broken into two main sections: `ligand-qsar` which is focused on the chemoinformatic investigation of ligand reactivity and yields; and `substrate-space` for substrate clustering and selection for HTE.

## Installation

This repository uses [uv](https://github.com/astral-sh/uv) to manage and install the dependencies. To install the dependencies, install uv and run the following command:

```bash
$ git clone git@github.com:Hartwig-Group/Abbvie-CN-Couplings-QSRR-and-HTE.git
$ cd Abbvie-CN-Couplings-QSRR-and-HTE
$ uv sync
```

Then to run any code, run then using the virtual environment created by uv:

```bash
$ uv run python my_script.py
```

Or read these [instructions](https://docs.astral.sh/uv/guides/integration/jupyter/) to run jupyter notebook:

```bash
$ uv run --with jupyter jupyter lab
```

## Repository Structure

```
Abbvie-CN-Couplings-QSRR-and-HTE/
|-- data/
|   |-- ligand-qsar/
|   |-- substrate-space/
|-- notebooks/
|   |-- ligand-qsar/
|   |-- substrate-space/
|-- pyproject.toml
|-- uv.lock
|-- README.md
```
The "Abbvie-CN-Couplings-QSRR-and-HTE" project is organized into several key directories, each serving a distinct purpose. Below is an overview of the main components:

**1. data/**
   - Folder for datasets and other relevant data files used in the project. This is broken into two folders, one for the ligand-qsar and the other for substrate-space.
   
**2. notebooks/ligand-qsar/**
   - Jupyter notebooks associated with the qsar modeling of ligand activity and yields.
     
**3. notebooks/substrate-space/**
  - Jupyter notebooks associated with (1) scraping literature reactions, (2) calculating RDF descriptors, (3) substrate clustering using those descriptors and selection for HTE, and (4) HTE results.

**4. pyproject.toml**
   - TOML file specifying the project's dependencies and environment configuration, facilitating reproducibility.

**5. uv.lock**
   - UV lock file to ensure reproducibility in environment creation.

**6. README.md**
   - The project's main documentation providing a high-level overview, usage instructions, and any other essential information for collaborators and users.

## Citation 

