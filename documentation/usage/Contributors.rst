  .. _contributors:

Contributors
============

Here is a list of the main contributors:

Main modules
************

Functionalities
---------------

* Sébastien Weber, Research Engineer at CEMES/CNRS

Cleaning
--------

* Sébastien Weber, Research Engineer at CEMES/CNRS
* David Trémouilles, Researcher at LAAS/CNRS



Plugins
*******

* Sébastien Weber, Research Engineer at CEMES/CNRS
* Sophie Meuret, Researcher at CEMES/CNRS
* David Bresteau, Research Engineer at Attolab facility, CEA Saclay

Documentation
*************

* Matthieu Cabos helped with this documentation

You want to contribute?
***********************

If you're willing to help, you can clone the up-to-date GitHub repo: https://github.com/CEMES-CNRS using git command line or
GitHub Desktop. I advise to create a dedicated conda environment for this and install PyMoDAQ's package as a
developer:


* ``cd`` to the location of the folder where you downloaded or cloned the repository.
* ``conda env create --name=pymodaq_dev --file=environment.yml``
* ``conda activate pymodaq_dev``
* install the main package as a developer using the command ``pip install -e .``.
* ``cd`` to the location of the folder where you downloaded or cloned the plugin repository.
* install the plugin package as a developer using the command ``pip install -e .``.

Any change on the code will be *seen* by python interpreter. When ready, you can ask to push your code into the main
development branch. A simpler way is to raise *Issues* on PyMoDAQ's github page.
