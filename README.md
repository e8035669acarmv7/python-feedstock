About python-feedstock
======================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/python-feedstock/blob/main/LICENSE.txt)

Home: https://www.python.org/

Package license: Python-2.0

Summary: General purpose programming language

Development: https://docs.python.org/devguide/

Documentation: https://www.python.org/doc/versions/

Python is a widely used high-level, general-purpose, interpreted, dynamic
programming language. Its design philosophy emphasizes code
readability, and its syntax allows programmers to express concepts in
fewer lines of code than would be possible in languages such as C++ or
Java. The language provides constructs intended to enable clear programs
on both a small and large scale.


Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=4155&branchName=main">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/python-feedstock?branchName=main">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_armv7l</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=4155&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/python-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_armv7l_" alt="variant">
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
| [![Conda Recipe](https://img.shields.io/badge/recipe-libpython--static-green.svg)](https://anaconda.org/e8035669acarmv7/libpython-static) | [![Conda Downloads](https://img.shields.io/conda/dn/e8035669acarmv7/libpython-static.svg)](https://anaconda.org/e8035669acarmv7/libpython-static) | [![Conda Version](https://img.shields.io/conda/vn/e8035669acarmv7/libpython-static.svg)](https://anaconda.org/e8035669acarmv7/libpython-static) | [![Conda Platforms](https://img.shields.io/conda/pn/e8035669acarmv7/libpython-static.svg)](https://anaconda.org/e8035669acarmv7/libpython-static) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-python-green.svg)](https://anaconda.org/e8035669acarmv7/python) | [![Conda Downloads](https://img.shields.io/conda/dn/e8035669acarmv7/python.svg)](https://anaconda.org/e8035669acarmv7/python) | [![Conda Version](https://img.shields.io/conda/vn/e8035669acarmv7/python.svg)](https://anaconda.org/e8035669acarmv7/python) | [![Conda Platforms](https://img.shields.io/conda/pn/e8035669acarmv7/python.svg)](https://anaconda.org/e8035669acarmv7/python) |

Installing python
=================

Installing `python` from the `e8035669acarmv7` channel can be achieved by adding `e8035669acarmv7` to your channels with:

```
conda config --add channels e8035669acarmv7
conda config --set channel_priority strict
```

Once the `e8035669acarmv7` channel has been enabled, `libpython-static, python` can be installed with `conda`:

```
conda install libpython-static python
```

or with `mamba`:

```
mamba install libpython-static python
```

It is possible to list all of the versions of `libpython-static` available on your platform with `conda`:

```
conda search libpython-static --channel e8035669acarmv7
```

or with `mamba`:

```
mamba search libpython-static --channel e8035669acarmv7
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search libpython-static --channel e8035669acarmv7

# List packages depending on `libpython-static`:
mamba repoquery whoneeds libpython-static --channel e8035669acarmv7

# List dependencies of `libpython-static`:
mamba repoquery depends libpython-static --channel e8035669acarmv7
```




Updating python-feedstock
=========================

If you would like to improve the python recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`e8035669acarmv7` channel, whereupon the built conda packages will be available for
everybody to install and use from the `e8035669acarmv7` channel.
Note that all branches in the conda-forge/python-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@chrisburr](https://github.com/chrisburr/)
* [@isuruf](https://github.com/isuruf/)
* [@jakirkham](https://github.com/jakirkham/)
* [@katietz](https://github.com/katietz/)
* [@mbargull](https://github.com/mbargull/)
* [@mingwandroid](https://github.com/mingwandroid/)
* [@msarahan](https://github.com/msarahan/)
* [@ocefpaf](https://github.com/ocefpaf/)
* [@pelson](https://github.com/pelson/)
* [@scopatz](https://github.com/scopatz/)
* [@xhochy](https://github.com/xhochy/)

