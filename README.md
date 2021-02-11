About pyrad_arm
===============

Home: https://github.com/MeteoSwiss/pyrad/

Package license: BSD-3-Clause

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/pyrad_arm-feedstock/blob/master/LICENSE.txt)

Summary: MeteoSwiss Pyrad, Python tool for radar data processing.

Development: https://github.com/MeteoSwiss/pyrad/

Documentation: https://pyrad-mch.readthedocs.io/en/stable/

This is the MeteoSwiss Pyrad. Pyrad is an open source Python
module for weather radar data processing. The module controls the
data flow. The inputs and outputs are specified using config files.
Most of the core data processing is performed using Py-ART, originally
developed in the framework of the Atmospheric Radiation Measurement (ARM)
Climate Research Facility for working with data from a number of
precipitation and cloud radars. This package is provided for convenience
to the Py-ART comunity. If you would like to get the full funcionality of
Pyrad please used pyrad_mch, which runs with the MeteoSwiss version of
Py-ART.


Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=9254&branchName=master">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/pyrad_arm-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64_numpy1.16python3.6.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=9254&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/pyrad_arm-feedstock?branchName=master&jobName=linux&configuration=linux_64_numpy1.16python3.6.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_numpy1.16python3.7.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=9254&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/pyrad_arm-feedstock?branchName=master&jobName=linux&configuration=linux_64_numpy1.16python3.7.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_numpy1.16python3.8.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=9254&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/pyrad_arm-feedstock?branchName=master&jobName=linux&configuration=linux_64_numpy1.16python3.8.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_numpy1.18python3.6.____73_pypy</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=9254&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/pyrad_arm-feedstock?branchName=master&jobName=linux&configuration=linux_64_numpy1.18python3.6.____73_pypy" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_numpy1.16python3.6.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=9254&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/pyrad_arm-feedstock?branchName=master&jobName=osx&configuration=osx_64_numpy1.16python3.6.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_numpy1.16python3.7.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=9254&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/pyrad_arm-feedstock?branchName=master&jobName=osx&configuration=osx_64_numpy1.16python3.7.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_numpy1.16python3.8.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=9254&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/pyrad_arm-feedstock?branchName=master&jobName=osx&configuration=osx_64_numpy1.16python3.8.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_numpy1.18python3.6.____73_pypy</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=9254&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/pyrad_arm-feedstock?branchName=master&jobName=osx&configuration=osx_64_numpy1.18python3.6.____73_pypy" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-pyrad_arm-green.svg)](https://anaconda.org/conda-forge/pyrad_arm) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/pyrad_arm.svg)](https://anaconda.org/conda-forge/pyrad_arm) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/pyrad_arm.svg)](https://anaconda.org/conda-forge/pyrad_arm) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/pyrad_arm.svg)](https://anaconda.org/conda-forge/pyrad_arm) |

Installing pyrad_arm
====================

Installing `pyrad_arm` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
```

Once the `conda-forge` channel has been enabled, `pyrad_arm` can be installed with:

```
conda install pyrad_arm
```

It is possible to list all of the versions of `pyrad_arm` available on your platform with:

```
conda search pyrad_arm --channel conda-forge
```


About conda-forge
=================

[![Powered by NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](http://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/)
and [TravisCI](https://travis-ci.com/) it is possible to build and upload installable
packages to the [conda-forge](https://anaconda.org/conda-forge)
[Anaconda-Cloud](https://anaconda.org/) channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating pyrad_arm-feedstock
============================

If you would like to improve the pyrad_arm recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/pyrad_arm-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@meteoswiss-mdr](https://github.com/meteoswiss-mdr/)

