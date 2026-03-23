# DS-4002-Project2
# Tech Layoff Forecasting (DS 4002 Project 2)

This repository contains all parts of our data science project, where we used tech layoffs from the years 2020 to the present to **forecast global monthly tech layoffs** for the remainder of **2026 and 2027.**

## Repository Contents (What’s in here)
At a high level, this repo includes:
- The raw tech layoff dataset (CSV)

---
## Section 1) Software and Platform

### Software
- **R** (RStudio recommended)

### Platform
- **macOS (Mac)**

### Required R Packages
Install these packages before running the code:
- `tidyverse`
- `lubridate`
- `scales`
- `forecast `
- `tseries`
- `zoo`
- `ggplot2`
- `patchwork`
- `knitr`
- `kableExtra`

(If you run into a missing-package error, install whatever package the error message names.)

## Section 2) Repository Structure and Documentation Map

This section describes the organization of the GitHub repository and the purpose of each folder and file.

### Folder and File Descriptions

#### DATA/
Contains the raw dataset used for the project.
- **Tech_layoffs.csv:** Original tech layoff dataset used for all exploratory analysis and modeling. This file is not manually modified.

#### OUTPUT/
Contains generated outputs from the exploratory data analysis.

#### MILESTONES/
Contains project milestone submissions documenting the project’s development.

#### SCRIPTS/
Contains analysis and modeling code.

#### Additional Files
- **README.md:** Provides an overview of the project, software requirements, repository structure, and instructions for reproducing results.


## Section 3) Instructions for Reproducing Results

This section provides step-by-step instructions to reproduce the exploratory analysis, modeling, and results for this project.

### Step 1: Install Required Software and Packages

- Install **R** and **RStudio**.
- Open RStudio and install all required packages listed in **Section 1** of this README.
- If any packages are missing, R will prompt you to install them when running the scripts.

### Step 2: Obtain and Place the Dataset

- Locate and download the file `Tech_layoffs.csv` from the DATA/ folder
- The raw dataset should **not** be manually edited.

### Step 3: Run exploratory data analysis (EDA)

Open the file ________ in RStudio and run it from top to bottom.  
This file contains all code used to perform exploratory data analysis, including:
- 

The rendered EDA outputs are saved as _________ and __________ in the `OUTPUT/` folder.

### Step 4: Preprocess Data

Open the file ______________ in RStudio and run the preprocessing sections of the file.  
This script performs all text preprocessing and feature engineering steps, including:
- 

All preprocessing steps are contained within this file and do not require running any additional scripts.

### Step 5: 



### Step 6: Review Final Results

- Confirm that the reproduced results align with those reported in the project documentation and presentation.
- Key findings include:
  - 
