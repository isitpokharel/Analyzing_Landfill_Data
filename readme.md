# Project Summary - LMOP Data Analysis using Leaflet

## Overview
This project utilizes the LMOP Database, containing crucial information about MSW (Municipal Solid Waste) landfills and LFG (Landfill Gas) energy projects in the United States. The analysis employs the Leaflet library in R to create maps, revealing geographic patterns in landfill locations. Note that the LMOP database doesn't cover all US landfills.

## Key Variables Analyzed
The focus is on key variables from the LMOP Database, including operational status, ownership type (Public vs Private), landfill waste amount, and LFG collection. State-level population data is incorporated to analyze these variables in per capita terms.

## Methods
The main R libraries used are dplyr for dataset manipulation and leaflet for map visualizations. Additional datasets include state-level Cartographic Boundary Files from the Census Bureau and state-level population data.

## Results

### 1. Number of Landfills by State
- Visualization categorizes states by population and represents the number of landfills with graduated symbols.
- Larger population states tend to have more landfills, e.g., California and Texas.

### 2. Dot Distribution Maps of Landfills by Operating Status
- Dot distribution map with circle markers color-coded by operational status (open/closed/unknown).
- Concentration of closed landfills in heavily populated states and industrial rust belt states.

### 3. Public Ownership of Landfills by State
- Categorizes states by the percentage of publicly owned landfills.
- Most states have 50% or more publicly owned landfills.

### 4. Total Landfill Waste Per Capita by States
- Choropleth map represents states based on waste per capita.
- Reveals states with high waste per capita, e.g., Michigan and Indiana.

### 5. Landfill Gas Collected by State
- Categorizes states by the percentage of LFG captured.
- Most states capture 50% or more LFG, with California leading in efficient gas collection.

## Conclusion
The analysis provides insights into the distribution, ownership, waste per capita, and LFG collection of landfills across states. Geographic patterns and correlations with population size are highlighted, offering valuable information for waste management considerations.

## Output
You can see the detailed analysis and the code used to generate the analysis in `Landfill_Data.html` file or generate the file yourself by compiling `Landfill_Data.Rmd` file.

## References
Meirelles, I. (2013). *Design for Information: An Introduction to the Histories, Theories, and Best Practices Behind Effective Information Visualizations.* Rockport Publishers.
