# Overview

Files used for creation of my 2023 BSides NoVa - Keyboard Walking Password Mitigation presentation

Various files/directories purpose:
    
    bsides_graphs.ipynb                 - Jupyter Notebook with code to create the graphs 
    bsides_keyboard_gifs.ipynb          - Jupyter Notebook with code to create the animated GIFs for the keyboards
    bsides_password_mitigation.ipynb    - Jupyter Notebook with code and markup for the presentation
    bsides_password_mitigation.html     - HTML conversion of the Jupyter Notebook used for the presentation
    images/                             - Directory with the images for presentation
    README.md

## Setting up the python environment

Roughly create a venv for jupyterhub and use pip3 to install the various necessary packages.  Certainly other python environments might work.

```
    [jeremy@devone ~]$ python -m venv create jh
    [jeremy@devone ~]$ cd jh
    [jeremy@devone jh]$ pip3 install jupyter numpy pandas matplotlib
    Defaulting to user installation because normal site-packages is not writeable
    ...
    [jeremy@devone jh]$ ls
    bin  include  lib  lib64  pyvenv.cfg
    [jeremy@devone jh]$ . bin/activate
    (jh) [jeremy@devone jh]$ jupyter notebook
```
