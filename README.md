# Treasure Island

[![Actions Status][actions-badge]][actions-link]
[![Documentation Status][rtd-badge]][rtd-link]

[![PyPI version][pypi-version]][pypi-link]
<!-- [![Conda-Forge][conda-badge]][conda-link] -->
[![PyPI platforms][pypi-platforms]][pypi-link]

<!-- [![GitHub Discussion][github-discussions-badge]][github-discussions-link] -->

<!-- SPHINX-START -->

<!-- prettier-ignore-start -->
[actions-badge]:            https://github.com/flint-crew/treasure-island/workflows/CI/badge.svg
[actions-link]:             https://github.com/flint-crew/treasure-island/actions
[conda-badge]:              https://img.shields.io/conda/vn/conda-forge/treasure-island
[conda-link]:               https://github.com/conda-forge/treasure-island-feedstock
[github-discussions-badge]: https://img.shields.io/static/v1?label=Discussions&message=Ask&color=blue&logo=github
[github-discussions-link]:  https://github.com/flint-crew/treasure-island/discussions
[pypi-link]:                https://pypi.org/project/treasure-island/
[pypi-platforms]:           https://img.shields.io/pypi/pyversions/treasure-island
[pypi-version]:             https://img.shields.io/pypi/v/treasure-island
[rtd-badge]:                https://readthedocs.org/projects/treasure-island/badge/?version=latest
[rtd-link]:                 https://treasure-island.readthedocs.io/en/latest/?badge=latest

<!-- prettier-ignore-end -->

A pirate version of [AegeanTools](https://github.com/PaulHancock/Aegean.git). If you use these tools please cite the original repo and papers.

Programs included:

- `aegean` - The Aegean source finding program. All your radio astronomy source finding needs in one spiffy program.
- `BANE` - The Background and Noise Estimation tool. For providing high quality background and noise images for use with Aegean, at a small fraction of the cost of a full box-car smooth.
- `MIMAS` - The Multi-resolution Image Masking tool for Aegean Software. For creating image regions which can be used to restrict the source finding of Aegean, to mask fits files, and to create ds9 region files.
- `SR6` - A tool for shrinking and growing fits files, such as those created with `BANE.py --compress`. Shrinking is done by decimation, growing is done by linear interpolation.
- `AeRes` - A tool for adding or subtracting sources from an image - "Aegean Residual". Catalogues must be in Aegean readable format (eg, written by Aegean, modified by user). This can be used to look for missed sources, mis-characterised sources, or for simulating new images.
- `AeReg` - A tool for adjusting an existing catalogue of sources by regrouping or resizing the components - "Aegean Regroup". Uses the same strategies as the Aegean priorized fitting pre-processing.

## Installing

You can install via pip using

```bash
pip install git+https://github.com/flint-crew/treasure-island # latest
```

```bash
pip install treasure-island # stable
```

## Credit

If you use `treasure_island` for your research please give credit to the orginal Aegean by citing:

- Paper 1, [Hancock et al 2012, MNRAS, 422, 1812](http://adsabs.harvard.edu/abs/2012MNRAS.422.1812H)
- Paper 2, [Hancock et al 2018, PASA, 35, 11H](http://adsabs.harvard.edu/abs/2018PASA...35...11H)


## Status

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3474072.svg)](https://doi.org/10.5281/zenodo.3474072)
