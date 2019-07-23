# What is in this repo ? How can I use the material ?

## Purpose

Give elements on machine learning to participants of the SAGEX workshop (2019-07-30). 

### Introduction

Before viewing the notebook an introduction using scaling law in physics will help set the scenery to understand the value of machine learning solutions.


### Tutorials

A few tutorials can be found in `notebooks/`, they explain basic notion in python.

### Basic machine learning

Notebooks on the classic iris and titanic as well as an analysis to the physical properties of water will be used to make first step on the subject.

### Plasticc

Simple analysis of the PLAsTiCC Astronomical Classification dataset

https://www.kaggle.com/c/PLAsTiCC-2018


This code will not to win the competition (already over). 

The aim is to show different data science analysis.

## Mininal requirement to run the project

You should have python3, pip3 and jupyter notebook install locally on your machine.

The other packages will be installed on a virtual environment to avoid conflict in the packages.

## ! WARNING: do **not** uninstall python on linux !

Be very carefull when uninstalling python on a linux machine. The linux kernel uses python. Uninstalling python can render you machine unusable.


## Configure virtual environment

* [ ] Run:

```
python3 -m venv venv3_plasticc
```

* [ ] Activate virtual environment:

```
source venv3_plasticc/bin/activate
```

* [ ] Install packages:

```
pip3 install -r requirements.txt 
```

* [ ] Add kernel to jupyter notebook:

```
python3 -m ipykernel install --user --name venv3_plasticc --display-name "plasticc"
```

## Download the repository (git or zip)

1. git: you can git clone the repo (see 5. to install)

```
git clone git@github.com:alexandreCameron/sagex.git
```

2. zip: if you are not familiar with git you can download a zip archive

![Alt text](src/download_repo.png?raw=true "Download repo")

## Reference

1. Virtual environment: https://ipython.readthedocs.io/en/stable/install/kernel_install.html
2. Python 3.6: https://www.python.org/downloads/release/python-368/
3. Jupyter notebook: https://jupyter.org/install
4. Git: https://git-scm.com/
5. Git install tutorial: https://www.atlassian.com/git/tutorials/install-git
