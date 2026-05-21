0. SECTIONS
-------------
1. Model
2. Funding
3. Reference
4. Terms of Use
5. Content
6. How to Start

1. MODEL
------------
Model title: PVWAT dust-to-soiling model

Publication Year: 2026

Creators
Names: Amy Banigo, Louise Crochemore, Béatrice Marticorena, Sanrdine Anquetin, Benoit Hingray
Organisations: Institute of Environmental Geosciences (IGE), University of Grenoble-Alpes ; Laboratoire Interuniversitaire des Systèmes Atmosphériques (LISA)

2. FUNDING
------------
Source: French National Research Agency (ANR)
Project title: NETWAT (West African Mineral Dust: a key in the NExus ClimaTe – WATer – Energy – NETWAT)
Link: https://netwat.osug.fr/
Dates: 2022-2026

3. REFERENCE
------------
If used, please reference :
Banigo A. T., Crochemore L., Marticorena B., Anquetin S., Hingray B., Simulating atmospheric dust impact on photovoltaic performance: A sensitivity analysis to guide modeling choices in a data scarce region  

4. TERMS OF USE
------------
Creative Commons License CC BY-NC-SA 4.0 
Attribution-NonCommercial-ShareAlike 4.0 International
https://creativecommons.org/licenses/by-nc-sa/4.0/

5. CONTENT
------------
This script is a notebook containing and explaining the necessary commands and functions to run the PVWAT dust-to-soiling model presented in Banigo et al.

Model Inputs
Inputs: Atmospheric time series (particulate matter concentrations, precipitation, wind speed) at a location
Outputs: Dust influx to solar panels, Dust accumulation on solar panels, Soiling ratio

This model script repository contains :
  - `ReadMe.md` : this file with information and instructions
  - `PVWAT_Simulation.Rmd` : The R notebook allowing to run the PVWAT model
  - `point_data.rds` : An example input data file provided for testing

6. HOW TO START
------------

# Requirements
1. Install R
2. Install RStudio

# Setup
3. Place `point_data.rds` in your chosen working directory
4. Open the `.Rmd` file in RStudio
5. Use the **Visual** mode for notebooks (optional but recommended)

# Running the Model
6. Set the input directory where specified, for example:
```r
input_dir <- "C:/Users/Documents"
```
7. Follow the instructions in the .Rmd file and run the code chunks sequentially