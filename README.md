About large-image-source-tiff-feedstock
=======================================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/large-image-source-tiff-feedstock/blob/main/LICENSE.txt)

Home: https://github.com/girder/large_image

Package license: Apache-2.0

Summary: Python modules to work with large, multiresolution images - Tiff source

Development: https://github.com/girder/large_image

Documentation: https://girder.github.io/large_image/

Python modules to work with large, multiresolution images - Tiff source. Large Image is developed and maintained by the Data & Analytics group at Kitware, Inc. for processing large geospatial and medical images.


Current build status
====================


<table><tr><td>All platforms:</td>
    <td>
      <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=14750&branchName=main">
        <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/large-image-source-tiff-feedstock?branchName=main">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-large--image--source--tiff-green.svg)](https://anaconda.org/conda-forge/large-image-source-tiff) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/large-image-source-tiff.svg)](https://anaconda.org/conda-forge/large-image-source-tiff) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/large-image-source-tiff.svg)](https://anaconda.org/conda-forge/large-image-source-tiff) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/large-image-source-tiff.svg)](https://anaconda.org/conda-forge/large-image-source-tiff) |

Installing large-image-source-tiff
==================================

Installing `large-image-source-tiff` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
conda config --set channel_priority strict
```

Once the `conda-forge` channel has been enabled, `large-image-source-tiff` can be installed with `conda`:

```
conda install large-image-source-tiff
```

or with `mamba`:

```
mamba install large-image-source-tiff
```

It is possible to list all of the versions of `large-image-source-tiff` available on your platform with `conda`:

```
conda search large-image-source-tiff --channel conda-forge
```

or with `mamba`:

```
mamba search large-image-source-tiff --channel conda-forge
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search large-image-source-tiff --channel conda-forge

# List packages depending on `large-image-source-tiff`:
mamba repoquery whoneeds large-image-source-tiff --channel conda-forge

# List dependencies of `large-image-source-tiff`:
mamba repoquery depends large-image-source-tiff --channel conda-forge
```


About conda-forge
=================

[![Powered by
NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](https://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[Azure](https://azure.microsoft.com/en-us/services/devops/), [GitHub](https://github.com/),
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/),
[Drone](https://cloud.drone.io/welcome), and [TravisCI](https://travis-ci.com/)
it is possible to build and upload installable packages to the
[conda-forge](https://anaconda.org/conda-forge) [anaconda.org](https://anaconda.org/)
channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance,
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information, please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating large-image-source-tiff-feedstock
==========================================

If you would like to improve the large-image-source-tiff recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/large-image-source-tiff-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks, and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@banesullivan](https://github.com/banesullivan/)
* [@giswqs](https://github.com/giswqs/)
* [@manthey](https://github.com/manthey/)

