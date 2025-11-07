# Toolkit for Prime Locations (AABPL)
(c) Gabriel M. Ahlfeldt, Thilo N. H. Albers, Kristian Behrens
Version 1.0.0, 2025-01

## Folder description

Each grid archive **grid_xxx.zip**  contains a shapefile for one USMSA.  
Below are the main variables in the attribute table:

| Column | Type | Description |
|:--------|:------|:-------------|
| **cell_id** | String | Unique identifier for the grid cell (combines coordinates for reproducibility) |
| **emp** | Float | Total employment count (National Economic Time Series) |
| **devle** | Binary (0/1) | Indicator whether the cell is developed land (1 = developed) |
| **emp_sh** | Float | Share of metropolitan employment (within grid) located in this cell  |
| **pop** | Float | Total population of the cell (from Bondarenko et al.) |
| **pop_sh** | Float | Cells's share of metropolitan population (within grid) located in this cell |

All data are from 2015. For a more detailed description of the data sources, see Ahlfeldt, Albers, Behrens (2025)

## Reference: 

Ahlfeldt G., Albers T., Behrens K. (2024): Prime locations. American Economic Review: Insights, forthcoming.

Bondarenko M., Priyatikanto R., Tejedor-Garavito N., Zhang W., McKeen T., Cunningham A., Woods T., Hilton J., Cihan D., Nosatiuk B., Brinkhoff T., Tatem A., Sorichetta A.. Constrained estimates of 2015-2030 total number of people per grid square at a resolution of 3 arc (approximately 100m at the equator) R2025A version v1. Global Demographic Data Project - Funded by The Bill and Melinda Gates Foundation (INV-045237). WorldPop - School of Geography and Environmental Science, University of Southampton. DOI:10.5258/SOTON/WP00839
 

