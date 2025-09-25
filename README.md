# Whale Shark Compliance Analysis

R analysis examining compliance patterns and violations in whale shark tourism interactions, comparing data between 2016 and 2022.

## Overview

This project analyzes whale shark tourism compliance data to understand patterns in boat and swimmer violations, spatial distributions, and temporal changes in compliance behavior.

## Files

- `whale_shark_analysis.Rmd` - Main analysis script with statistical modeling and visualization
- `whale_shark_data/` - Data files containing boat, swimmer, and field observation records:
  - `General2016.csv`, `General2022.csv` - General violation and encounter data
  - `Boat2016.csv`, `Boat2022.csv` - Boat-specific violation records
  - `Swimmer2016.csv`, `Swimmer2022.csv` - Swimmer violation records
  - `Infield2016.csv`, `Infield_2022.csv` - In-field observation data
  - `Infield2016_no_boats.csv` - 2016 boat count data over time
  - `encount_boat_2year_fre.csv`, `encount_swim_2year_fre.csv` - Encounter frequency summaries


## Usage

Open `whale_shark_analysis.Rmd` in RStudio and knit to HTML to generate the full analysis report.

