***************************************************************************
Welcome to the Fast All-sky Radiation Model for Solar applications (FARMS)!
***************************************************************************

.. image:: https://github.com/NatLabRockies/farms/workflows/Documentation/badge.svg
    :target: https://natlabrockies.github.io/farms/

.. image:: https://github.com/NatLabRockies/farms/workflows/Pytests/badge.svg
    :target: https://github.com/NatLabRockies/farms/actions?query=workflow%3A%22Pytests%22

.. image:: https://github.com/NatLabRockies/farms/workflows/Lint%20Code%20Base/badge.svg
    :target: https://github.com/NatLabRockies/farms/actions?query=workflow%3A%22Lint+Code+Base%22

.. image:: https://img.shields.io/pypi/pyversions/NLR-farms.svg
    :target: https://pypi.org/project/NLR-farms/

.. image:: https://badge.fury.io/py/NLR-farms.svg
    :target: https://badge.fury.io/py/NLR-farms

.. image:: https://codecov.io/gh/NatLabRockies/farms/branch/master/graph/badge.svg?token=WQ95L11SRS
    :target: https://codecov.io/gh/NatLabRockies/farms


The Fast All-sky Radiation Model for Solar applications (FARMS) is used to
compute cloudy irradiance.

.. inclusion-intro

Installing farms
================

Option 1: Install from PyPI (recommended for analysts):
-------------------------------------------------------

1. Create a new environment:
    ``conda create --name farms``

2. Activate the environment:
    ``conda activate farms``

3. Install farms:
    ``pip install NLR-farms``

Option 2: Clone repo (recommended for developers)
-------------------------------------------------

1. Create an environment and install package
    1) Create a conda env: ``conda create -n farms``
    2) Run the command: ``conda activate farms``
    3) Clone the repository and ``cd`` into it.
    4) prior to running ``pip`` below, make sure the branch is correct (install
       from master!)
    5) Install ``farms`` and its dependencies by running:
       ``pip install .`` (or ``pip install -e .`` if running a dev branch
       or working on the source code)

Recommended Citation
====================

Yu Xie, Manajit Sengupta, Jimy Dudhia, "A Fast All-sky Radiation Model
for Solar applications (FARMS): Algorithm and performance evaluation",
Solar Energy, Volume 135, 2016, Pages 435-445, ISSN 0038-092X,
https://doi.org/10.1016/j.solener.2016.06.003.
`Science Direct Link. <http://www.sciencedirect.com/science/article/pii/S0038092X16301827>`_