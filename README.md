# AAS227Workshop

Materials for the Bayesian Methods in Astronomy workshop at AAS227

View all the content [here](https://github.com/jakevdp/AAS227Workshop/blob/master/Index.ipynb)


## Requirements

For this workshop we will be using Python, and in particular *Python version 3.4-3.5*. In addition, we will make use of the following packages, along with their dependencies.

**Note that familiarity with the following packages is considered a pre-requisite to the workshop. We will not be spending time helping people with setting up or installing these packages.**

- [NumPy](http://numpy.org) (Numerical Python) for efficient manipulation of array-based data
- [SciPy](http://scipy.org) (Scientific Python) for optimization and other routines
- [Matplotlib](http://matplotlib.org) for scientific visualization
- [IPython notebook](http://ipython.org) as an interactive computing environment

To install these dependencies, I *highly* recommend using the [miniconda](http://conda.pydata.org/miniconda.html) Python installer *(be sure to download the Python 3.5 version of miniconda)*. Once this is installed, run the following commands in your terminal:

```
$ conda install numpy scipy matplotlib ipython-notebook pip
```

On top of these prerequisites, we will be introducing two relatively lightweight packages designed to enable efficient Bayesian computation in Python.
They are:

- [emcee](http://dan.iel.fm/emcee/) for Markov Chain Monte Carlo sampling of Bayesian posteriors
- [corner.py](https://pypi.python.org/pypi/corner/1.0.0) for visualization of multidimensional posteriors

These can be installed via the Python Package Index, using the ``pip`` command:

```
$ pip install emcee
$ pip install corner
```

## Workshop Material

All the material for this workshop, as well as the exercises we will work on together, is contained in IPython notebooks within this repository.
Please clone this repository (if you are familiar with Git) or download the zip file (link is to the right on the main repository page) to download this content; note that I will likely update the material in the days prior to the workshop, so please plan to git-pull or re-download the zip file the morning of the workshop.