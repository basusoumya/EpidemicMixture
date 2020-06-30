# MixtureEpidemics

MixtureEpidemics is the companion code for the experiments in the paper "Learning Mixtures of Graphs from Epidemic Cascades".

Among other, it provides code for generating two random graphs, as well as epidemics spreading on the mixture of these two graphs. 

As it, it runs the three experiments in the paper:
 - error vs number of samples
 - histogram of errors for fixed number of samples
 - number of samples needed for given precision vs degree of the graphs

## Installation

The code is in a Jupyter notebook. If not already installed, use the package manager [pip](https://pip.pypa.io/en/stable/) to install jupyter notebook. 

```bash
pip install notebook
```

You can find the installation documentation for the
[Jupyter platform, on ReadTheDocs](https://jupyter.readthedocs.io/en/latest/install.html).

## Usage

To use, lauch Jupyter notebook on the folder in which the code is:

```bash
cd [path_to_code]/CodeMixture
jupyter notebook
```

Then, select the file "MixtureEpidemics.ipynb", and click "Run".
