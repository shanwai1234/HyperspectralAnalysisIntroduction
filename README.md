# A (very) Brief Introduction to Hyperspectral Image Analysis
Brief Introduction to Hyperspectral Image Analysis.

This introduction was presented at the Phenome Digital Phenotyping Workshop at Phenome 2018 (http://phenome2018.org) in Tucson, AZ on Saturday, February 14, 2018. 

Authors: Taylor Glenn and Alina Zare

Please reference this work if any part of it is used elsewhere: 
[![DOI](https://zenodo.org/badge/123327729.svg)](https://zenodo.org/badge/latestdoi/123327729)

A. Zare and T. Glenn. (2018, March 1). GatorSense/HyperspectralAnalysisIntroduction v0.3 (Version v0.3). Zenodo. http://doi.org/10.5281/zenodo.1186417

The introduction material was placed into four (Python 3) Jupyter notebooks:

1. HSI Intro.ipynb
2. Unmixing.ipynb
3. Target Detection.ipynb
4. Classification.ipynb

The file requirements.txt gives all of the package dependencies for the Python environment. You should be able to install them with the command:

```
> pip install -r requirements.txt
```

We recommend using a virtual environment to install and run the python packages. Installation instructions using a virtualenv:

```
> python3 -m venv hsienv
> source hsienv/bin/activate
> pip install Cython
> pip install -r requirements.txt
```

Start jupyter:

```
> jupyter notebook
```

To exit the virtualenv when finished run:

```
> deactivate
```
