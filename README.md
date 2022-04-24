About ffmpeg
============

Home: https://www.ffmpeg.org/

Package license: LGPL-2.1-or-later

Feedstock license: [BSD-3-Clause](https://github.com/ramonaoptics/ffmpeg-feedstock/blob/master/LICENSE.txt)

Summary: Cross-platform solution to record, convert and stream audio and video.

Development: https://git.ffmpeg.org/ffmpeg.git

Documentation: https://ffmpeg.org/documentation.html

Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/ramonaoptics/feedstock-builds/_build/latest?definitionId=&branchName=master">
            <img src="https://dev.azure.com/ramonaoptics/feedstock-builds/_apis/build/status/ffmpeg-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64</td>
              <td>
                <a href="https://dev.azure.com/ramonaoptics/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/ramonaoptics/feedstock-builds/_apis/build/status/ffmpeg-feedstock?branchName=master&jobName=linux&configuration=linux_64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64</td>
              <td>
                <a href="https://dev.azure.com/ramonaoptics/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/ramonaoptics/feedstock-builds/_apis/build/status/ffmpeg-feedstock?branchName=master&jobName=linux&configuration=linux_aarch64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le</td>
              <td>
                <a href="https://dev.azure.com/ramonaoptics/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/ramonaoptics/feedstock-builds/_apis/build/status/ffmpeg-feedstock?branchName=master&jobName=linux&configuration=linux_ppc64le_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64</td>
              <td>
                <a href="https://dev.azure.com/ramonaoptics/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/ramonaoptics/feedstock-builds/_apis/build/status/ffmpeg-feedstock?branchName=master&jobName=osx&configuration=osx_64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_arm64</td>
              <td>
                <a href="https://dev.azure.com/ramonaoptics/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/ramonaoptics/feedstock-builds/_apis/build/status/ffmpeg-feedstock?branchName=master&jobName=osx&configuration=osx_arm64_" alt="variant">
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
| [![Conda Recipe](https://img.shields.io/badge/recipe-ffmpeg-green.svg)](https://anaconda.org/ramonaoptics/ffmpeg) | [![Conda Downloads](https://img.shields.io/conda/dn/ramonaoptics/ffmpeg.svg)](https://anaconda.org/ramonaoptics/ffmpeg) | [![Conda Version](https://img.shields.io/conda/vn/ramonaoptics/ffmpeg.svg)](https://anaconda.org/ramonaoptics/ffmpeg) | [![Conda Platforms](https://img.shields.io/conda/pn/ramonaoptics/ffmpeg.svg)](https://anaconda.org/ramonaoptics/ffmpeg) |

Installing ffmpeg
=================

Installing `ffmpeg` from the `ramonaoptics` channel can be achieved by adding `ramonaoptics` to your channels with:

```
conda config --add channels ramonaoptics
conda config --set channel_priority strict
```

Once the `ramonaoptics` channel has been enabled, `ffmpeg` can be installed with `conda`:

```
conda install ffmpeg
```

or with `mamba`:

```
mamba install ffmpeg
```

It is possible to list all of the versions of `ffmpeg` available on your platform with `conda`:

```
conda search ffmpeg --channel ramonaoptics
```

or with `mamba`:

```
mamba search ffmpeg --channel ramonaoptics
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search ffmpeg --channel ramonaoptics

# List packages depending on `ffmpeg`:
mamba repoquery whoneeds ffmpeg --channel ramonaoptics

# List dependencies of `ffmpeg`:
mamba repoquery depends ffmpeg --channel ramonaoptics
```




Updating ffmpeg-feedstock
=========================

If you would like to improve the ffmpeg recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`ramonaoptics` channel, whereupon the built conda packages will be available for
everybody to install and use from the `ramonaoptics` channel.
Note that all branches in the ramonaoptics/ffmpeg-feedstock are
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

* [@183amir](https://github.com/183amir/)
* [@benjaminrwilson](https://github.com/benjaminrwilson/)
* [@carlodri](https://github.com/carlodri/)
* [@danielballan](https://github.com/danielballan/)
* [@h-vetinari](https://github.com/h-vetinari/)
* [@jakirkham](https://github.com/jakirkham/)
* [@matthiasdiener](https://github.com/matthiasdiener/)
* [@ocefpaf](https://github.com/ocefpaf/)
* [@patricksnape](https://github.com/patricksnape/)
* [@sdvillal](https://github.com/sdvillal/)

