========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |appveyor| |requires|
        | |coveralls| |codecov|
        | |landscape| |scrutinizer| |codacy| |codeclimate|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|

.. |docs| image:: https://readthedocs.org/projects/datascibox/badge/?style=flat
    :target: https://readthedocs.org/projects/datascibox
    :alt: Documentation Status


.. |travis| image:: https://travis-ci.org/barisozmen/datascibox.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/barisozmen/datascibox

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/barisozmen/datascibox?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/barisozmen/datascibox

.. |requires| image:: https://requires.io/github/barisozmen/datascibox/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/barisozmen/datascibox/requirements/?branch=master

.. |coveralls| image:: https://coveralls.io/repos/barisozmen/datascibox/badge.svg?branch=master&service=github
    :alt: Coverage Status
    :target: https://coveralls.io/r/barisozmen/datascibox

.. |codecov| image:: https://codecov.io/github/barisozmen/datascibox/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/barisozmen/datascibox

.. |landscape| image:: https://landscape.io/github/barisozmen/datascibox/master/landscape.svg?style=flat
    :target: https://landscape.io/github/barisozmen/datascibox/master
    :alt: Code Quality Status

.. |codacy| image:: https://img.shields.io/codacy/REPLACE_WITH_PROJECT_ID.svg
    :target: https://www.codacy.com/app/barisozmen/datascibox
    :alt: Codacy Code Quality Status

.. |codeclimate| image:: https://codeclimate.com/github/barisozmen/datascibox/badges/gpa.svg
   :target: https://codeclimate.com/github/barisozmen/datascibox
   :alt: CodeClimate Quality Status

.. |version| image:: https://img.shields.io/pypi/v/datascibox.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/datascibox

.. |commits-since| image:: https://img.shields.io/github/commits-since/barisozmen/datascibox/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/barisozmen/datascibox/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/datascibox.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/datascibox

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/datascibox.svg
    :alt: Supported versions
    :target: https://pypi.org/project/datascibox

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/datascibox.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/datascibox

.. |scrutinizer| image:: https://img.shields.io/scrutinizer/g/barisozmen/datascibox/master.svg
    :alt: Scrutinizer Status
    :target: https://scrutinizer-ci.com/g/barisozmen/datascibox/


.. end-badges

A box of data science utilities

* Free software: MIT license

Installation
============

::

    pip install datascibox

Documentation
=============


https://datascibox.readthedocs.io/


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
