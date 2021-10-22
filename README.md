About gnuradio-paint
====================

Home: https://github.com/drmpeg/gr-paint

Package license: GPL-3.0-or-later

Feedstock license: [BSD-3-Clause](https://github.com/ryanvolz/gnuradio-paint-feedstock-local-feedstock/blob/master/LICENSE.txt)

Summary: OFDM Spectrum Painter for GNU Radio

Development: https://github.com/drmpeg/gr-paint

Documentation: https://github.com/drmpeg/gr-paint

The goal of this project is to build a software-defined OFDM transmitter that "paints" monochrome images into the waterfall of a receiver. It is based on https://github.com/polygon/spectrum_painter
After installation, a GNU Radio block called "Spectrum Painter" will be available in the "Paint" category. The block converts a byte stream of image data into a 4K IFFT OFDM IQ sequence for transmission.


Current build status
====================


<table>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-gnuradio--paint-green.svg)](https://anaconda.org/ryanvolz/gnuradio-paint) | [![Conda Downloads](https://img.shields.io/conda/dn/ryanvolz/gnuradio-paint.svg)](https://anaconda.org/ryanvolz/gnuradio-paint) | [![Conda Version](https://img.shields.io/conda/vn/ryanvolz/gnuradio-paint.svg)](https://anaconda.org/ryanvolz/gnuradio-paint) | [![Conda Platforms](https://img.shields.io/conda/pn/ryanvolz/gnuradio-paint.svg)](https://anaconda.org/ryanvolz/gnuradio-paint) |

Installing gnuradio-paint
=========================

Installing `gnuradio-paint` from the `ryanvolz` channel can be achieved by adding `ryanvolz` to your channels with:

```
conda config --add channels ryanvolz
conda config --set channel_priority strict
```

Once the `ryanvolz` channel has been enabled, `gnuradio-paint` can be installed with:

```
conda install gnuradio-paint
```

It is possible to list all of the versions of `gnuradio-paint` available on your platform with:

```
conda search gnuradio-paint --channel ryanvolz
```




Updating gnuradio-paint-feedstock
=================================

If you would like to improve the gnuradio-paint recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`ryanvolz` channel, whereupon the built conda packages will be available for
everybody to install and use from the `ryanvolz` channel.
Note that all branches in the ryanvolz/gnuradio-paint-feedstock are
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

* [@ryanvolz](https://github.com/ryanvolz/)

