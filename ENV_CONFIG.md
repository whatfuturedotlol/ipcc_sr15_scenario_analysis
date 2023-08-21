# Environment Configuration

## Architecture

- **Type:** Intel
- **Python Version:** 3.7

## Pyenv

- **Installation:** 
  - Installed `pyenv` + `pyenv-virtualenv` via `brew`.
  - Command: `pyenv virtualenv anaconda3-2018.12 "project name"`
  - Downgraded Python version to 3.7 with `conda install python=3.7`.

## Anaconda

- **Version:** anaconda3-2018.12
- **Installation Guide:** [Anaconda Archive](https://docs.anaconda.com/free/anaconda/reference/packages/oldpkglists/)

## Environment Files

### Conda Environment

- **File:** `environment.yml`
  - Contains all the Conda packages required for the project.

### Pip Packages

- **File:** `pipfile.txt`
  - Contains additional packages installed via pip.

### Comments

I had trouble getting a stable set of packages to run, and looking at conda list and pip list, i have several duplicate packages installed by both pip and conda.

Specifically
- pyyaml 6.0 on both
- pandas 1.3.5 on pip and 0.24.2 on conda
- pyam 0.5.0 on both, use pip install pyam-iamc=0.5.0
- matplotlib 3.5.3 on conda and 3.0.2 on pip

Jupyter notebook uses the more recent versions except in the case of matplotlib where it uses an older version. I don't want mess with the stability I found but 
thought I'd add some comments to clarify. 
