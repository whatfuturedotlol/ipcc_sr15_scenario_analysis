Environment Configuration:
Architecture:
Type: Intel
Python:
Version: 3.7
Pyenv:
pyenv + pyenv-virtualenv installed with brew. then ran pyenv virtualenv anaconda3-2018.12 "project name"
i then needed to downgrade python to 3.7 using conda install python=3.7

Anaconda:
Version: anaconda3-2018.12
Installation Guide: Anaconda Archive
Conda Environment:
File: environment.yml
This file contains all the Conda packages required for the project.
Pip Packages:
File: pipfile.txt
This file contains additional packages installed via pip.settings or configurations related to pyenv
