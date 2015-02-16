arm_archive.py is Python module for accessing the ARM archive in Python

Requirements
------------

Python 2.7 (3.3 might work)
Suds (https://fedorahosted.org/suds/), tested with version 0.4


Install
-------
Copy the file arm_archive.py to the site-packages file, add a .pth file, or
add the directory to the PYTHON_PATH.

Use
---
The function in the module can be used in Python after importing the module.

The module can also be used from the command line using:

    > python -m arm_archive

This can be aliased in bash using:
    alias apu='python -m arm_archive'
