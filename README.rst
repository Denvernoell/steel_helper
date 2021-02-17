========
Overview
========

.. start-badges

.. .. list-table::
..     :stub-columns: 1

..     * - docs
..       - |docs|
..     * - tests
..       - | |travis| |appveyor| |requires|
..         | |codecov|
..     * - package
..       - | |version| |wheel| |supported-versions| |supported-implementations|
..         | |commits-since|
.. .. |docs| image:: https://readthedocs.org/projects/python-steel-helper/badge/?style=flat
..     :target: https://readthedocs.org/projects/python-steel-helper
..     :alt: Documentation Status

.. .. |travis| image:: https://api.travis-ci.com/denvernoell/python-steel-helper.svg?branch=master
..     :alt: Travis-CI Build Status
..     :target: https://travis-ci.com/github/denvernoell/python-steel-helper

.. .. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/denvernoell/python-steel-helper?branch=master&svg=true
..     :alt: AppVeyor Build Status
..     :target: https://ci.appveyor.com/project/denvernoell/python-steel-helper

.. .. |requires| image:: https://requires.io/github/denvernoell/python-steel-helper/requirements.svg?branch=master
..     :alt: Requirements Status
..     :target: https://requires.io/github/denvernoell/python-steel-helper/requirements/?branch=master

.. .. |codecov| image:: https://codecov.io/gh/denvernoell/python-steel-helper/branch/master/graphs/badge.svg?branch=master
..     :alt: Coverage Status
..     :target: https://codecov.io/github/denvernoell/python-steel-helper

.. .. |version| image:: https://img.shields.io/pypi/v/steel_helper.svg
..     :alt: PyPI Package latest release
..     :target: https://pypi.org/project/steel_helper

.. .. |wheel| image:: https://img.shields.io/pypi/wheel/steel_helper.svg
..     :alt: PyPI Wheel
..     :target: https://pypi.org/project/steel_helper

.. .. |supported-versions| image:: https://img.shields.io/pypi/pyversions/steel_helper.svg
..     :alt: Supported versions
..     :target: https://pypi.org/project/steel_helper

.. .. |supported-implementations| image:: https://img.shields.io/pypi/implementation/steel_helper.svg
..     :alt: Supported implementations
..     :target: https://pypi.org/project/steel_helper

.. .. |commits-since| image:: https://img.shields.io/github/commits-since/denvernoell/python-steel-helper/v0.0.0.svg
..     :alt: Commits since latest release
..     :target: https://github.com/denvernoell/python-steel-helper/compare/v0.0.0...master



.. end-badges

Python module to help calculaterequirements for design of steel structures

* Free software: GNU Lesser General Public License v3 or later (LGPLv3+)

Installation
============

::

    pip install steel_helper

You can also install the in-development version with::

    pip install https://github.com/denvernoell/python-steel-helper/archive/master.zip


Documentation
=============


https://python-steel-helper.readthedocs.io/


.. Development
.. ===========

.. To run all the tests run::

..     tox

.. Note, to combine the coverage data from all the tox environments run:

.. .. list-table::
..     :widths: 10 90
..     :stub-columns: 1

..     - - Windows
..       - ::

..             set PYTEST_ADDOPTS=--cov-append
..             tox

..     - - Other
..       - ::

..             PYTEST_ADDOPTS=--cov-append tox