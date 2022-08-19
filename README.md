[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3893509.svg)](https://doi.org/10.5281/zenodo.3893509)

# Hodge diamond cutter

A collection of Python classes and functions in Sage to deal with Hodge diamonds (and Hochschild homology) of smooth projective varieties, together with many constructions.

If you have used this code in any way (including the interactive versions on my blog), please consider citing it as explained on [Zenodo](https://doi.org/10.5281/zenodo.3893509). You can choose to cite a specific version, or always the latest version. For the latter you can use `doi:10.5281/zenodo.3893509`.


## Getting started

It suffices to load ``diamond.py`` in Sage to get started. The documentation with lots of examples can be [read online](https://pbelmans.ncag.info/hodge-diamond-cutter/) or as [a pdf](https://pbelmans.ncag.info/hodge-diamond-cutter/hodgediamondcutter.pdf).


## Contributing

Please feel free to make suggestions for more examples of Hodge diamonds. Preferably with a link to a closed formula, generating series or method of computation.

Feature requests are also very welcome.

## A warning

In the [words of Simon Pepin Lehalleur on Twitter](https://twitter.com/plain_simon/status/1355599647893549056),
in order to use the Hodge diamond cutter, you must always answer the question

> You are solving a PDE; do you want to proceed?

positively.

## Instructions to myself

To build the documentation:

```
sage -sh -c "make html"
cp -r _build/html/ docs
sage -sh -c "make latexpdf"
cp _build/latex/hodgediamondcutter.pdf docs
```

To perform the unit tests:

```
sage -t diamond.py
```

And suggestions on improving the documentation are also welcome.

