# GT4Py: Python tool for implementing finite-difference computations for weather and climate

This repository includes the demos shown in the AMS101 13.10 presentation.

## Get Code

```bash
$ git clone https://github.com/jdahm/AMS101-gt4py-demos.git
$ cd AMS101-gt4py-demos
```

## Create a virtual environment

```bash
$ python --version # compatible versions are 3.6.x, 3.7.x, and 3.8.x
$ python -m venv env # create a virtual env
$ source env/bin/activate # activate it
```

## Install dependencies

GT4Py is not yet on Pypi, so it needs to be installed through git.

```bash
$ pip install jupyter matplotlib "git+https://github.com/gridtools/gt4py.git"
```

The `numpy` will work out-of-the-box, but the GridTools backends require boost headers, so if these are not installed in a standard system path, then the BOOST_ROOT` environment variable will have to be exported in the shell before launching jupyter in the next step.

## Launch Jupyter

```bash
$ jupyter notebook # this will open in your browser
```
