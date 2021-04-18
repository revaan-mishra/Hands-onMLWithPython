# Hands-onMLWithPython

## About
Python implementations of some of the fundamental Machine Learning models and algorithms from scratch.

The purpose of this project is not to produce as optimized and computationally efficient algorithms as possible
but rather to present the inner workings of them in a transparent and accessible way.

## Setup

To run the code, you need the packages ``Python 3.6+``, ``numpy``, ``scipy``, ``scikit-learn``, ``matplotlib``,
``pandas``, ``pillow``, ``Seaborn``, ``Statsmodels`` and ``Sympy``.
Some of the visualizations of decision trees and neural networks structures also require ``graphviz``. 

The easiest way to set up an environment is by installing [Anaconda](https://www.continuum.io/downloads).

### Installing packages with conda:
If you already have a Python environment set up, and you are using the ``conda`` package manager, you can get all packages by running

    conda install numpy scipy scikit-learn matplotlib pandas pillow graphviz python-graphviz


### Installing packages with pip
If you already have a Python environment and are using pip to install packages, you need to run

    pip install numpy scipy scikit-learn matplotlib pandas pillow graphviz

You also need to install the graphiz C-library, which is easiest using a package manager.
If you are using OS X and homebrew, you can ``brew install graphviz``. If you are on Ubuntu or debian, you can ``apt-get install graphviz``.
Installing graphviz on Windows can be tricky and using conda / anaconda is recommended.


## Scikit Learn Machine Learning Cheat Sheet

![alt text](https://github.com/GeorgeSeif/Python-Machine-Learning/blob/master/ml_cheatsheet.png)

## Feedback

If you have a favorite algorithm that should be included or spot a mistake in one of the notebooks, please let me know by creating a new issue.

## License

See the LICENSE file for license rights and limitations (MIT).
