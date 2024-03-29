# Drosera Species Climate Impact
This repository contains the occurrence data and source code used in our research on the impacts of climate change on the distribution of Drosera species. Our study aims to understand how changing climatic conditions affect these unique carnivorous plants and to assess potential risks to their future distribution.

## Contents

- **Occurrence Data:** The raw data collected on the occurrence of Drosera species across different geographic locations.
- **Source Code:** Python and R scripts used throughout our analysis, including data cleaning, bioclimatic variable selection, and model calibration.

### 1. Cleaning and Preparing Occurrence Data

- **Script:** `data_cleaning.py`
- **Description:** This script processes the raw occurrence data, removing duplicates and filtering out records with missing or erroneous information. It prepares the dataset for further analysis.

### 2. Selecting and Cropping Bioclimatic Variables

- **Script:** `bioclim_variables.R`
- **Description:** This R script selects relevant bioclimatic variables from WorldClim and other climatic databases. It crops these variables to the study area, matching the geographic extent of the occurrence data.

### 3. Calibrating Models, Extrapolation, and Risk Assessment

- **Script:** `model_calibration.py`
- **Description:** This Python script involves calibrating species distribution models using the cleaned occurrence data and selected bioclimatic variables. It includes steps for model extrapolation to future climate scenarios and assessing risks to Drosera species distribution.

## Usage

To use the scripts in this repository, please ensure you have Python and R installed on your machine. Detailed instructions on how to run each script are provided within the script files themselves.

## Data Sources

The occurrence data for Drosera species was sourced from [Global Biodiversity Information Facility (GBIF)](https://www.gbif.org) and other public databases. Bioclimatic variables were obtained from [WorldClim](https://www.worldclim.org).

## Citation

If you use the data or scripts from this repository in your research, please cite our paper: [Full Citation of the Paper]

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.

## Contact

For any queries related to this repository, please reach out to [Ulises Olivares](uolivares@unam.mx).
