.. stork documentation master file, created by
   sphinx-quickstart on Fri Jun 29 16:33:02 2018.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to stork's documentation!
====================================

Command line helpers for Databricks!

What is stork?
-----------------

Stork is a set of command line helpers for Databricks. Some commands are for managing libraries in Databricks in an automated fashion. This allows you to move away from the point-and-click interface for your development work and for deploying production-level libraries for use in scheduled Databricks jobs. Another command allows you to create an interactive cluster that replicates the settings used on a job cluster.

.. _install:

Installation
------------

Stork is hosted on PyPi, so to get the latest version simply install via ``pip``::

    pip install stork

You can also install from source, by cloning the git repository ``https://github.com/ShopRunner/stork.git`` and installing via ``easy_install``::

    git clone https://github.com/ShopRunner/stork.git
    cd stork
    easy_install .

.. _start:

Quickstart
----------

To get started, first run ``stork configure`` and answer the questions. 

Then you are ready to upload libraries to Databricks, using the ``stork upload`` and ``stork upload_and_update`` commands.

Please see :ref:`getting_started` for an introduction to the package, and :ref:`usage_details` for specifics on availible options.

Table of Contents
-----------------
.. toctree::
   :maxdepth: 2
   :caption: Contents:

   getting_started.rst   
   stork.rst
   tutorial.rst
   contrib.rst

Indices and tables
------------------

* :ref:`genindex`
* :ref:`search`
