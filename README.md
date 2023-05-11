emsarray-notebooks
==================

This repository contains example Jupyter Notebooks for [emsarray][emsarray].

## Notebooks

### `plot.ipynb`

This notebook shows the basics of plotting datasets and variables using emsarray.

### `clip.ipynb`

This notebook shows how to clip a dataset to a region,
to extract a geographic subset of your data.

### `animation.ipynb`

This notebook demonstrates some simple animations that emsarray can generate.
The animations can be across time, or across another axis such as depth.

### `bokeh.ipynb`

This notebook draws plots using the popular [bokeh][bokeh] library,
as an alternative to [matplotlib][matplotlib].

## Running the notebooks

### Local copy

To explore these notebooks locally,
clone the repository, install the dependencies, and launch Jupyter Lab:

```shell
$ git clone https://github.com/csiro-coasts/emsarray-notebooks
$ cd emsarray-notebooks
$ conda env create --name emsarray-notebooks --file ./environment.yaml
$ conda activate emsarray-notebooks
$ jupyter-lab
```

### Binder

[![Binder](https://mybinder.org/badge_logo.svg)][emsarray-binder]

You can explore these notebooks online without downloading them using [Binder][emsarray-binder].

[bokeh]: https://bokeh.org/
[emsarray]: https://github.com/csiro-coasts/emsarray
[emsarray-binder]: https://mybinder.org/v2/gh/csiro-coasts/emsarray-notebooks/HEAD
[matplotlib]: https://matplotlib.org/
