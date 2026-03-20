# VTPEH 6270 Check Point 05 GitHub Repository

## Project Title
Exploratory Analysis and Simulation Using NYSDOH BRFSS 2023 Data

## Author
Puying Li  
Cornell University

## Contact Information
pl657@cornell.edu

## Project Overview
This repository contains data, scripts, and output files from multiple checkpoints in VTPEH 6270. The project uses the NYSDOH BRFSS 2023 dataset to explore selected public health questions and to demonstrate a simple simulation study.

## Research Questions
1. Is smoking status associated with self-reported general health among adults in New York State?
2. Do adults who reported any physical activity or exercise have a lower prevalence of any poor mental health days than those who reported no exercise?

## Files Included
- CP02: early data cleaning and exploratory work on blood pressure, BMI, age group, and weight
- CP03: data exploration of smoking status and self-reported health
- CP04: simulation of the relationship between exercise and poor mental health days

## Data Source
New York State Department of Health BRFSS 2023 survey data. The original BRFSS dataset is very large (about 167MB), so it is not included in this repository. Instead, a smaller subset of the data (3,000 observations with selected variables) is provided so that the analysis and simulation scripts can still run properly.

## Notes
All files are included for course project documentation and reproducibility.

## Reproducibility Notes
The repository includes a reduced subset dataset (`brfss_subset_small.csv`) so the scripts can run without the original large BRFSS file.
To reproduce the work:
1. Open the relevant `.Rmd` file in RStudio.
2. Make sure required R packages are installed.
3. Run the code in the corresponding checkpoint file (CP02, CP03, or CP04).

## Required Packages
This project uses common R packages for data analysis and visualization, including packages such as `ggplot2`, `dplyr`, and `knitr` where applicable.

## Repository Structure
- `data/`: contains the cleaned subset dataset used for analysis
- `scripts/`: R Markdown files for CP02, CP03, and CP04
- `output/`: rendered PDF reports and related output files
This structure is designed to improve clarity, organization, and reproducibility.

## Notes on Data
The original BRFSS dataset is not included because of its large file size. A reduced subset is provided for reproducibility and contains the key variables needed for analysis.

## AI Tool Disclosure
ChatGPT was used to help organize repository structure, troubleshoot code issues, and improve wording. All final code, decisions, and interpretations were reviewed and edited by the author.

## Required Packages

The following R packages are required to run the analysis:
- tidyverse
- ggplot2
- dplyr
- readr
