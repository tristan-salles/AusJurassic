[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.164700.svg)](https://doi.org/10.5281/zenodo.164700)

**T. Salles, N. Flament and D. Muller (2016), badlands-model/g-cubed-2017: G3 paper dataset, doi:10.5281/zenodo.164700.**

# Supplementary materials: Australian Landscape Dynamic

<div align="center">
    <img width=950 src="visual/topochange.png" alt="Topographic evolution at given time intervals" title="Topographic evolution at given time intervals"</img>
</div>

This repository contains all the materials required to reproduce the models published in our G-cubed paper:

Salles, T., N. Flament, and D. Muller (2017), **Influence of mantle flow on thedrainage of eastern Australia since the Jurassic Period**, Geochem. Geophys. Geosyst., 18, doi:10.1002/2016GC006617 


You will need to download and install <a href='https://github.com/badlands-model/badlands/releases' target="_blank">Badlands v1.0<a/> to run these experiments.

[![DOI](https://zenodo.org/badge/16678/badlands-model/badlands.svg)](https://zenodo.org/badge/latestdoi/16678/badlands-model/badlands)

## Content

+ **XmL file**: Main entry point for defining the initial and forcing conditions used by **Badlands** to run any model (this is required)
+ **topodyn**: this folder contains the normalized dynamic topography value at 10 Ma increments which are used in the paper.
+ **paleodata**: this folder contains the sea-level fluctuations (Haq, 1987) - the rainfall parameters - and the DEM of Australian paleotopography (150 Ma)
+ **NetCDF-outputs**: contains a subset of model results (shipped as NetCDF files) for a high-resolution test presented in the paper
+ **visual**: contains an image from the model output

## Animation

An animation of the high-resolution model is available as a <a href='https://youtu.be/JcxwM7krP0E' target="_blank">YouTube video<a/> or for download from the following <a href='https://cloudstor.aarnet.edu.au/plus/index.php/s/MWrfvJrwwisIAqW' target="_blank">link<a/> (be aware this a 250 MB file).

---
