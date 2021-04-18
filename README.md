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

For the chapter on text processing you also need to install ``nltk`` and ``spacy``:

    conda install nltk spacy


### Installing packages with pip
If you already have a Python environment and are using pip to install packages, you need to run

    pip install numpy scipy scikit-learn matplotlib pandas pillow graphviz

You also need to install the graphiz C-library, which is easiest using a package manager.
If you are using OS X and homebrew, you can ``brew install graphviz``. If you are on Ubuntu or debian, you can ``apt-get install graphviz``.
Installing graphviz on Windows can be tricky and using conda / anaconda is recommended.

### Regression
* Simple linear regression with t-statistic generation
<img src="https://slideplayer.com/slide/6053182/20/images/10/Simple+Linear+Regression+Model.jpg" width="400" height="300"/>
([https://github.com/revaan-mishra/Hands-onMLWithPython/tree/main/Regression/Simple%20Linear%20Regression/Python)]

* [Multi-variate regression with regularization](https://github.com/revaan-mishra/Hands-onMLWithPython/tree/main/Regression/Multiple%20Linear%20Regression/Python)
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/f8/L1_and_L2_balls.svg/300px-L1_and_L2_balls.svg.png"/>

* Polynomial regression using ***scikit-learn pipeline feature*** ([https://github.com/revaan-mishra/Hands-onMLWithPython/tree/main/Regression/Polynomial%20Regression/Python))

* [Decision trees regression](https://github.com/revaan-mishra/Hands-onMLWithPython/tree/main/Classification/Decision%20Tree%20Classification/Python)

* [Random Forest regression](https://github.com/revaan-mishra/Hands-onMLWithPython/tree/main/Regression/Random%20Forest%20Regression/Python)

* [Support Vector regression](https://github.com/revaan-mishra/Hands-onMLWithPython/tree/main/Regression/Support%20Vector%20Regression%20(SVR)/Python)
