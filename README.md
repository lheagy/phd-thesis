# Electromagnetic imaging of subsurface injections
_Lindsey Heagy_

This repository contains all of the latex used to generate the [thesis pdf](./thesis/thesis.pdf). All of the notebooks used to generate the figures in the thesis are available and Jupyter notebooks or python scripts. They are listed [by chapter](#Notebooks-by-Chapter) below.  

## Abstract

The extraction of hydrocarbons from low-permeability formations is commonly achieved through hydraulic fracturing. In a hydraulic fracturing operation, fluid and particles, called proppant (commonly sand) are injected to create fracture pathways and to keep those pathways open so that hydrocarbons can flow from the reservoir to the wellbore. One of the key unknowns in hydraulic fracturing operations is the distribution and extent of proppant within the reservoir. If the electrical conductivity of the injected materials is distinct from the host rock, then electromagnetic geophysical methods can be used. In order for electromagnetics to be a viable imaging technique for this application, we must be able to: (a) collect data that are sensitive to the injected materials, and (b) have a method for estimating a representative model of the injected materials from those data through an inversion process. Numerical modelling is an essential tool for assessing feasibility of electromagnetics and for developing a suitable inversion procedure for extracting meaningful information from the collected data.

A complicating factor of using electromagnetics in reservoir settings is that steel- cased wells are commonly present. Steel has vastly different electrical and magnetic properties than the surrounding rock and therefore significantly alters the behavior of electromagnetic fields and fluxes. The success of electromagnetic methods for imaging subsurface injections, therefore, heavily relies on our ability to understand and simulate the physical behavior of fields and fluxes in these settings.

Using hydraulic fracturing as a motivating application, this thesis examines aspects both the imaging problem for subsurface injections as well as the fundamental behav- ior of electromagnetic fields and fluxes in settings with steel-cased wells. I present a strategy for estimating the electrical conductivity of a fractured volume of rock and incorporate this into the inverse problem. I also develop a numerical approach for accurately simulating electromagnetic surveys in settings with steel-cased wells. Using this software, I examine aspects of the fundamental physics, including how the magnetic properties of a pipe complicate the behavior of the fields and fluxes, and how this impacts measured data.

All of the software developed during the course of this research is open-source.

## Notebooks by Chapter
### Chapter 2: A physical property model for a fractured volume of rock
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1434457.svg)](https://doi.org/10.5281/zenodo.1434457)
[![Build Status](https://travis-ci.org/simpeg-research/heagy-2018-fracture-physprops.svg?branch=master)](https://travis-ci.org/simpeg-research/heagy-2018-fracture-physprops)
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/simpeg-research/heagy-2018-fracture-physprops/master)

- GitHub: https://github.com/simpeg-research/heagy-2018-fracture-physprops
- DOI: [10.5281/zenodo.1434456](https://doi.org/10.5281/zenodo.1434456)

### Chapter 3: Modelling electromagnetics on cylindrical meshes
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1220427.svg)](https://doi.org/10.5281/zenodo.1220427)
[![Build Status](https://travis-ci.org/simpeg-research/heagy-2018-emcyl.svg?branch=master)](https://travis-ci.org/simpeg-research/heagy-2018-emcyl)
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/simpeg-research/heagy-2018-emcyl/master?filepath=index.ipynb)

- GitHub: https://github.com/simpeg-research/heagy-2018-emcyl 
- DOI: [10.5281/zenodo.1220427](https://doi.org/10.5281/zenodo.1220427)

### Chapter 4: Direct current resistivity with steel-cased wells
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1324543.svg)](https://doi.org/10.5281/zenodo.1324543)
[![Build Status](https://travis-ci.org/simpeg-research/heagy-2018-dc-casing.svg?branch=master)](https://travis-ci.org/simpeg-research/heagy-2018-dc-casing)
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/simpeg-research/heagy-2018-dc-casing/master?filepath=index.ipynb)

- GitHub: https://github.com/simpeg-research/heagy-2018-dc-casing
- DOI: [10.5281/zenodo.1324543](https://doi.org/10.5281/zenodo.1324543)

### Chapter 5: Electromagnetics with steel cased wells
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1434454.svg)](https://doi.org/10.5281/zenodo.1434454)
[![Build Status](https://travis-ci.org/simpeg-research/heagy-2018-em-casing.svg?branch=master)](https://travis-ci.org/simpeg-research/heagy-2018-em-casing)
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/simpeg-research/heagy-2018-em-casing/master)

- GitHub: https://github.com/simpeg-research/heagy-2018-em-casing
- DOI: [10.5281/zenodo.1434454](https://doi.org/10.5281/zenodo.1434454)

### Chapter 6: An inversion approach for subsurface injections
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1434458.svg)](https://doi.org/10.5281/zenodo.1434458)
[![Build Status](https://travis-ci.org/simpeg-research/heagy-2018-injection-inversions.svg?branch=master)](https://travis-ci.org/simpeg-research/heagy-2018-injection-inversions)
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/simpeg-research/heagy-2018-injection-inversions/master)

- GitHub: https://github.com/simpeg-research/heagy-2018-injection-inversions 
- DOI: [10.5281/zenodo.1434458](https://doi.org/10.5281/zenodo.1434458)

### Appendix D: A framework for simulation and inversion in electromagnetics
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1434469.svg)](https://doi.org/10.5281/zenodo.1434469)

- GitHub: https://github.com/simpeg-research/heagyetal-2017-simpegem
- DOI: [10.5281/zenodo.1434469](https://doi.org/10.5281/zenodo.1434469)

 
