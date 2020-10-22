About python-bidi
=================

Home: https://github.com/MeirKriheli/python-bidi

Package license: LGPLv3

Feedstock license: [BSD-3-Clause](https://github.com/nsls-ii-forge/python-bidi-feedstock/blob/master/LICENSE.txt)

Summary: Pure python implementation of the BiDi layout algorithm

Development: https://github.com/MeirKriheli/python-bidi

Documentation: http://python-bidi.readthedocs.io/en/latest/

Bi-directional (BiDi) layout implementation in pure python

Current build status
====================


<table><tr><td>All platforms:</td>
    <td>
      <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=262&branchName=master">
        <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/python-bidi-feedstock?branchName=master">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-python--bidi-green.svg)](https://anaconda.org/nsls2forge/python-bidi) | [![Conda Downloads](https://img.shields.io/conda/dn/nsls2forge/python-bidi.svg)](https://anaconda.org/nsls2forge/python-bidi) | [![Conda Version](https://img.shields.io/conda/vn/nsls2forge/python-bidi.svg)](https://anaconda.org/nsls2forge/python-bidi) | [![Conda Platforms](https://img.shields.io/conda/pn/nsls2forge/python-bidi.svg)](https://anaconda.org/nsls2forge/python-bidi) |

Installing python-bidi
======================

Installing `python-bidi` from the `nsls2forge` channel can be achieved by adding `nsls2forge` to your channels with:

```
conda config --add channels nsls2forge
```

Once the `nsls2forge` channel has been enabled, `python-bidi` can be installed with:

```
conda install python-bidi
```

It is possible to list all of the versions of `python-bidi` available on your platform with:

```
conda search python-bidi --channel nsls2forge
```




Updating python-bidi-feedstock
==============================

If you would like to improve the python-bidi recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`nsls2forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `nsls2forge` channel.
Note that all branches in the nsls-ii-forge/python-bidi-feedstock are
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


