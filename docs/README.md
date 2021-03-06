# ANTA Documentation

This section provides generic documentation related to the Arista Network Test Automation framework (ANTA)


## User documentation

- [requirements-and-installation.md](requirements-and-installation.md): This file provides instructions about the requirements and installation procedure.
- [usage.md](usage.md): Command usages
- [demo.md](demo.md): This file content full output of commands provided by ANTA package.


## Automated documentation

- [ANTA documentation overview](api/README.md): It is an overview of the [ANTA](../anta) Python package documentation in markdown format. It is generated by the script [generate-functions-documentation.py](generate-functions-documentation.py) and the docstrings in the python package [ANTA](../anta).
- [api/tests.md](api/tests.md): It is the [ANTA](../anta) Python package detailled documentation in markdown format. It is generated by the script [generate-functions-documentation.py](generate-functions-documentation.py) and the docstrings in the python package [ANTA](../anta).
- [generate-functions-documentation.py](generate-functions-documentation.py): The functions to test EOS devices are coded in the python package [ANTA](../anta). These functions have docstrings.
  - These docstrings are used by the script [generate-functions-documentation.py](generate-functions-documentation.py) to generate the functions documentation in markdown format in the directory [api](api/).
  - This requires the installation of the python package [lazydocs](https://github.com/ml-tooling/lazydocs) that is indicated in the file [requirements-dev.txt](../requirements-dev.txt)
