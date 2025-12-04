# PSet - Python

## Preamble

The present document is a part of the PSet (Project Setter) project. It describes how the python project template was built, where its content comes from and how it is intended to be used.

## Table of contents

## License

Multiple licenses are available for your PSet python project. The list of licenses has been chosen from [TLDRLegal](https://www.tldrlegal.com/license-tags/open-source).
The content of the licenses have been extracted from [ChooseALicense](https://choosealicense.com), the website I'd recommend if you don't know which license to choose.

## Setup.py 

The setup script, presently refered to as `setup` or `setup.py` has been extracted from [this repository](https://github.com/kennethreitz/setup.py/blob/master/setup.py)

## Requirements.txt

The `requirements.txt` file contains all the needed dependencies for your project. It's initialised at the start of the project with the previously present libraries; through, since [PEP 668](https://peps.python.org/pep-0668/) you should not python base environments are meant to be considered as "externally managed" and *your requirements.txt should be empty*. If that is not the case, please review all the python packages managed globally peryou system and remove them. 

## Linter
the linter furnished with this template is [Google's pylintRC](https://google.github.io/styleguide/pylintrc)
