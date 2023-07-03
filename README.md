**[overview](#overview) | [installation](#installation) | [running the notebooks](#running-the-notebooks) | [issues](#issues) | [contributing](#for-contributors)**

# em-apps
[![binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/geoscixyz/em-apps/main?filepath=index.ipynb)
[![SimPEG](https://img.shields.io/badge/powered%20by-SimPEG-blue.svg)](http://simpeg.xyz)

## Note

The em-apps were created principally for the
[DISC 2017](https://disc2017.geosci.xyz/), the SEG *Distinguished Instructor
Short Course* about *Electromagnetics Fundamentals and Applications*. The apps
are currently only sparsely maintained, and depend therefore on older versions
of most requirements.

The recommended way of installation is therefore using `conda` together with
the `environment.yml` file, see below. This environment will install many old
versions of codes, so don't expect to be able to use that environment with your
newest tool; rather, it will be a dedicated environment for these apps.

## Overview

This is a repo of notebooks and interactive examples for http://em.geosci.xyz. The examples are based on code available in
[em_examples](http://github.com/geoscixyz/em_examples). Numerical simulations are based on [SimPEG](http://simpeg.xyz).

<img src="https://em.geosci.xyz/_images/DC_LayeredEarth_notebook.png" width=60% align="center">


### Installation

To run them locally, you will need to have python installed, preferably through [miniconda](https://docs.conda.io/en/latest/miniconda.html#latest-miniconda-installer-links) or [mamba forge](https://mamba.readthedocs.io/en/latest/installation.html).

You can then clone this repository. From a command line, run

```
git clone https://github.com/geoscixyz/em-apps.git
```

Then `cd` into `em-apps`

```
cd em-apps
```

To setup your software environment, we recommend you use the provided conda environment

```
conda env create -f environment.yml
conda activate geosci-labs
```

You can then launch Jupyter
```
jupyter notebook
```

Jupyter will then launch in your web-browser.

## Running the notebooks

Each cell of code can be run with `shift + enter` or you can run the entire notebook by selecting `cell`, `Run All` in the toolbar.

![cell-run-all](https://em.geosci.xyz/_images/run_all_cells.png)

For more information on running Jupyter notebooks, see the [Jupyter Documentation](https://jupyter.readthedocs.io/en/latest/)

## Issues

If you run into problems or bugs, please let us know by [creating an issue](https://github.com/geoscixyz/em-apps/issues/new) in this repository.

## For Contributors

We are glad you are interested in contributing! 

This repo tracks [geosci-labs](https://github.com/geoscixyz/geosci-labs). To contribute code, ideas or bug-fixes, please head over to the [geosci-labs](https://github.com/geoscixyz/geosci-labs) repository. 

