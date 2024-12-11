# deshima-sensitivity

[![Release](https://img.shields.io/pypi/v/deshima-sensitivity?label=Release&color=cornflowerblue&style=flat-square)](https://pypi.org/project/deshima-sensitivity/)
[![Python](https://img.shields.io/pypi/pyversions/deshima-sensitivity?label=Python&color=cornflowerblue&style=flat-square)](https://pypi.org/project/deshima-sensitivity/)
[![Downloads](https://img.shields.io/pypi/dm/deshima-sensitivity?label=Downloads&color=cornflowerblue&style=flat-square)](https://pepy.tech/project/deshima-sensitivity)
[![DOI](https://img.shields.io/badge/DOI-10.5281/zenodo.3966839-cornflowerblue?style=flat-square)](https://doi.org/10.5281/zenodo.3966839)
[![Tests](https://img.shields.io/github/actions/workflow/status/deshima-dev/deshima-sensitivity/tests.yaml?label=Tests&style=flat-square)](https://github.com/deshima-dev/deshima-sensitivity/actions)

Sensitivity calculator for DESHIMA-type spectrometers

## Overview

deshima-sensitivity is a Python package which enables to calculate observation sensitivity of DESHIMA-type spectrometers.
Currently it is mainly used to estimate the observation sensitivity of [DESHIMA](http://deshima.ewi.tudelft.nl) and its successors.

An online Jupyter notebook is available for DESHIMA collaborators to calculate the sensitivity and the mapping speed of the DESHIMA 2.0 by themselves.
Click the budge below to open it in [Google colaboratory](http://colab.research.google.com/) (a Google account is necessary to re-run it).

### Stable version (recommended)

[![open stable version in colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/deshima-dev/deshima-sensitivity/blob/v0.3.1/sensitivity.ipynb)

### Latest version

[![open latest version in colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/deshima-dev/deshima-sensitivity/blob/master/sensitivity.ipynb)

In the case of running it in a local Python environment, please follow the requirements and the installation guide below.

## Requirements

- **Python:** 3.10, 3.11, 3.12, and 3.13 (tested by the authors)
- **Dependencies:** See [pyproject.toml](https://github.com/deshima-dev/deshima-sensitivity/blob/v0.3.1/pyproject.toml)

## Installation

```shell
pip install deshima-sensitivity
```
