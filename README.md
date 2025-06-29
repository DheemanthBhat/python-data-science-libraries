# python-data-science-libraries

## 1 Introduction

### 1.1 Summary

Repository to utilize various python Data Science libraries.

### 1.2 Index

This repository covers following data science libraries:

#### 1.2.1 Data manipulation libraries

1. [NumPy](01_numpy/README.md)
1. [pandas](02_pandas/README.md)

#### 1.2.2 Data visualization libraries

1. [Matplotlib](03_matplotlib/README.md)
1. [seaborn](04_seaborn/README.md)

#### 1.2.3 Data modeling libraries

1. [scikit-learn]()
1. [TensorFlow]()
1. [PyTorch]()

### 1.3 Technologies

1. Python: Programming language (version >= 3.12).
1. Libraries:
   1. [NumPy][1]: Python library used for scientific computing.
   1. [pandas][2]: Python library used for data manipulation and analysis.
   1. [Matplotlib][3]: Python library used for data visualization.
   1. [seaborn][4]: Python library used for enhanced data visualization.

## 2 Setup

### 2.1 Local setup

#### STEP 1: Clone repository

Clone this repository and traverse to the project folder using below commands:

```sh
git clone https://github.com/DheemanthBhat/python-data-science-libraries.git
cd python-data-science-libraries
```

#### STEP 2: Setup virtual environment

#### Windows

```sh
python -m venv .venv
.venv\Scripts\activate
```

#### Linux

```sh
python -m venv .venv
source .venv/bin/activate
```

#### STEP 3: Install python packages

```sh
pip install -r requirements.txt
```

[1]: https://numpy.org/
[2]: https://pandas.pydata.org/
[3]: https://matplotlib.org/
[4]: https://seaborn.pydata.org/

#### STEP 4: Jupyter server

Start jupyter notebook (within virtual environment) using below command:

```sh
jupyter notebook
```
