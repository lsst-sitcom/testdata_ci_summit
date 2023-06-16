`testdata_ci_summit`
====================

``testdata_ci_summit`` provides a minimal amount of test data sufficient
to run the Rubin Observatory `ci_summit` tests.

.. _ci_summit: https://github.com/lsst-sitcom/ci_summit/

Contents of this package
------------------------

The ``raw/`` directory contains raw files from AuxTel observations as copied
from ``/sdf/group/rubin/lsstdata/offline/instrument/LATISS/storage/`` at USDF.
Their data IDs are:
- ``{'day_obs': 20200315, 'seq_num': 120, 'detector': 0}``
- ``{"day_obs": 20210121, "seq_num": 742, "detector": 0}``
- ``{"day_obs": 20210121, "seq_num": 743, "detector": 0}``

Git LFS
-------

To clone and use this repository, you'll need Git Large File Storage (LFS).

Our [Developer Guide](https://developer.lsst.io/tools/git_lfs.html)
explains how to set up Git LFS for LSST development.
