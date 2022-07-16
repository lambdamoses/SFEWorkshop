# BioC 2022 SpatialFeatureExperiment workshop

Here we demonstrate the [`SpatialFeatureExperiment`](https://github.com/pachterlab/SpatialFeatureExperiment) (SFE) S4 class that brings [Simple Features (as in the `sf` package)](https://r-spatial.github.io/sf/) to [`SpatialExperiment`](https://github.com/drighelli/SpatialExperiment), and exploratory spatial data analysis (ESDA) with the SFE object with the [`Voyager`](https://github.com/pachterlab/Voyager) package. This workshop has 3 parts:

1. An introduction to spatial transcriptomics, geospatial data analysis, and how the geospatial methods may or may not apply to spatial transcriptomics.
2. Introduction to the `sf` data frame and the SFE object. A [published Visium dataset](https://doi.org/10.1038/s42003-021-02810-x) already as an SFE object provided in the [`SFEData`](https://github.com/pachterlab/SFEData) package is used for the demonstrations here and in part 3.
3. Plotting and basic ESDA with the `Voyager` package. The ESDA includes computing Moran's I and Geary's C for spatial autocorrelation, permutation testing for Moran's I, correlograms, and Moran plot.

## Prerequisites
* Basic knowledge of R syntax and data structures
* Familiarity with [`SingleCellExperiment`](https://bioconductor.org/packages/release/bioc/html/SingleCellExperiment.html) and preferably also `SpatialExperiment` classes
* Familiarity with `sf` is preferable for in depth data analyses using SFE but optional for this workshop

## Using the Docker image
TBD