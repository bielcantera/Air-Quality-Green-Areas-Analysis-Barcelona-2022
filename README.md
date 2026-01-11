# Air Quality & Green Areas Analysis — Barcelona (2022)

## 🌐 Full Project Report (Web)
The complete analysis, including code snippets, visualizations and conclusions, is available as an interactive HTML report:

👉 **[Open project report](https://bielcantera.github.io/Air-Quality-Green-Areas-Analysis-Barcelona-2022/AIR-QUALITY-BCN-MARKDOWN.html)**

## Project Overview
This project analyzes air pollution levels in Barcelona during 2022 and explores their relationship with green areas and tree density across city districts.

## Objectives
- Analyze air pollution trends in Barcelona during 2022
- Compare pollution levels across districts
- Study pollution patterns over time (monthly, daily, hourly)
- Evaluate the relationship between air pollution and green density
- Analyze major pollutants (NO2, SO2, PM10, PM2.5, O3, CO, NOx)

## Tech Stack
- R
- tidyverse
- ggplot2

## Data Sources
- Barcelona open data on air quality (2022)
- Tree census datasets (parks and street trees)
- District-level population and surface data

Raw datasets are not included to avoid large files and licensing issues.

## Methodology
1. Merge monthly air quality datasets into a single 2022 dataset
2. Clean missing values and reshape hourly data
3. Map monitoring stations to districts
4. Aggregate tree counts and compute tree density (trees/km²)
5. Perform spatial and temporal analysis by pollutant
6. Visualize results using ggplot2

## Key Findings
- No strong direct relationship between total tree count and pollution levels
- Tree density provides better insight than absolute tree count, but is still insufficient alone
- Population density and traffic patterns play a major role
- Pollution peaks align with commuting hours (morning and evening)

## Repository Structure
/scripts        -> R scripts for data cleaning and analysis  
/visualizations -> Generated plots  
/docs           -> Project documentation  

## Future Improvements
- Add geospatial analysis (maps)
- Include traffic and meteorological data
- Apply regression or causal inference models
- Extend analysis to multiple years

## Authors
- Alejandro García  
- Biel Cantera  
- Laura Martín  
- Lia Siroo

## Project Note
This project was originally developed in R as an academic analysis.
The original script files were lost due to a hardware change, but the full documented analysis
(code, visualizations and interpretation) is preserved in the HTML report.

## Personal Contribution
- Data cleaning and transformation in R
- District-level and temporal analysis
- Visualization and interpretation of results
  
The analysis aims to provide data-driven insights that can support urban planning and environmental policy decisions.

