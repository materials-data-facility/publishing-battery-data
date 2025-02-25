# Building a Publication-Ready Dataset from CAMP

[Paulson et al. JPC (2022)](ihttps://doi.org/10.1016/j.jpowsour.2022.231127) created machine learning models using data from different types of cells made by the [CAMP Facility](https://www.anl.gov/cse/cell-analysis-modeling-and-prototyping-camp-facility).
We convert that data into publication-ready forms in this repository by storing the data in well-defined formats that package metadata about the cell's design and testing.

See [our battery data toolkit](https://github.com/materials-data-facility/battery-data-toolkit) for a full description on the tools for how to use them.

## Accessing the Data

The data are available via the Materials Data Facility: [landing page](https://doi.org/10.18126/s90e-dq90)

You can download the entire data as a single ZIP file ([link](https://data.materialsdatafacility.org/mdf_open/camp_2023/1.1/all_hdf5s.zip)),
or use [Globus Transfer](https://docs.globus.org/how-to/get-started/) to get different subsets.

## Installation

Install the environment for this repository using Anaconda. 

```bash
conda env create --file environment.yml --force
```
