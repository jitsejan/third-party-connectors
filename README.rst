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
        | |codecov|
    * - package
      - | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/third-party-connectors/badge/?style=flat
    :target: https://readthedocs.org/projects/third-party-connectors
    :alt: Documentation Status

.. |travis| image:: https://api.travis-ci.com/jitsejan/third-party-connectors.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.com/github/jitsejan/third-party-connectors

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/jitsejan/third-party-connectors?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/jitsejan/third-party-connectors

.. |requires| image:: https://requires.io/github/jitsejan/third-party-connectors/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/jitsejan/third-party-connectors/requirements/?branch=master

.. |codecov| image:: https://codecov.io/gh/jitsejan/third-party-connectors/branch/master/graphs/badge.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/jitsejan/third-party-connectors

.. |commits-since| image:: https://img.shields.io/github/commits-since/jitsejan/third-party-connectors/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/jitsejan/third-party-connectors/compare/v0.1.0...master



.. end-badges

A variety of third party connectors.

* Free software: BSD 2-Clause License

Installation
============

::

    pip install thirdpartyconnectors

You can also install the in-development version with::

    pip install https://github.com/jitsejan/third-party-connectors/archive/master.zip


Documentation
=============


https://third-party-connectors.readthedocs.io/


Development
===========

To run all the tests run::

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
