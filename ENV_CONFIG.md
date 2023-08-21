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

pyam-iamc=0.5.0


