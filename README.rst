Astromatic-Wrapper
==================

.. image:: http://img.shields.io/badge/powered%20by-AstroPy-orange.svg?style=flat
    :target: http://www.astropy.org
    :alt: Powered by Astropy Badge

Astromatic-Wrapper is a package for running python pipelines that depend on 
the `Astromatic Software Suite`_. The package mainly consists of an API to 
allow the user to run AstrOmatic codes such as `SExtractor`_, `SCAMP`_, `SWarp`_, 
`PSFEx`_, etc. from python scripts that make it easy to modify the configuration
files and parameters used.

It also contains a Pipeline class for building custom pipelines that include
AstrOmatic codes that can be used to process large datasets.

See the full `documentation`_ for more information.
sergotail fork is intented to upgrade this api


Status reports for developers
-----------------------------

.. image:: https://travis-ci.org/fred3m/astromatic_wrapper.png?branch=master
    :target: https://travis-ci.org/fred3m/astromatic_wrapper
    :alt: Test Status

.. image:: https://coveralls.io/repos/fred3m/astromatic_wrapper/badge.svg?branch=master&service=github 
    :target: https://coveralls.io/github/fred3m/astromatic_wrapper?branch=master

.. _Astromatic Software Suite: http://www.astromatic.net/

.. _SExtractor: http://www.astromatic.net/software/sextractor

.. _SCAMP: http://www.astromatic.net/software/scamp

.. _SWarp: http://www.astromatic.net/software/swarp

.. _PSFEx: http://www.astromatic.net/software/psfex

.. _documentation: http://astromatic-wrapper.readthedocs.org/en/latest/