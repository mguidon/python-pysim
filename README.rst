========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis|
        | |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|

.. |docs| image:: https://readthedocs.org/projects/python-pysim/badge/?style=flat
    :target: https://readthedocs.org/projects/python-pysim
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/mguidon/python-pysim.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/mguidon/python-pysim

.. |codecov| image:: https://codecov.io/github/mguidon/python-pysim/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/mguidon/python-pysim

.. |version| image:: https://img.shields.io/pypi/v/pysim.svg
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/pysim

.. |commits-since| image:: https://img.shields.io/github/commits-since/mguidon/python-pysim/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/mguidon/python-pysim/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/pysim.svg
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/pysim

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/pysim.svg
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/pysim

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/pysim.svg
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/pysim


.. end-badges

An example package. Generated with cookiecutter-pylibrary.

* Free software: MIT license

Installation
============

::

    pip install pysim

Documentation
=============

https://python-pysim.readthedocs.io/

Development
===========

To run the all tests run::

    tox

Note, to combine the coverage data from all the tox environments run:

.. list-table::
    :widths: 10 90
    :stub-columns: 1

    - - Windows
      - ::

            set PYTEST_ADDOPTS=--cov-append
            tox

    - - Other
      - ::

            PYTEST_ADDOPTS=--cov-append tox
