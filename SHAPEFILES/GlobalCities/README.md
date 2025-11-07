# Toolkit for Prime Locations (AABPL)
(c) Gabriel M. Ahlfeldt, Thilo N. H. Albers, Kristian Behrens
Version 1.0.0, 2025-01

## Folder description

Each grid archive **grid_xxx.zip**  contains a shapefile for one Global city.  
Below are the main variables in the attribute table:

| Column | Type | Description |
|:--------|:------|:-------------|
| **metro_id** | Integer | Unique ID for the metropolitan area (corresponds to the grid number `n`) |
| **cell_id** | String | Unique identifier for the grid cell (combines coordinates for reproducibility) |
| **devle** | Binary (0/1) | Indicator whether the cell is developed land (1 = developed) |
| **psempsh** | Float | Percentage of cell's tradable-services employment at total city  (within grid)  tradable-servics employment (%) (predicted by Ahlfeldt, Albers, Behrens) |
| **plid_glob** | String | Prime location identifier (delineated by Ahlfeldt, Albers, Behrens)  |
| **photo_sh** | Float | Cell's share at city's total geotagged photos  (from Erica Fisher's geotaggers world atlas) |
| **pop_dens** | Float | Cell's population density (from Bondarenko et al.)  |
| **pop_sh** | Float | Cells's share of metropolitan population (within grid) located in this cell |
| **emp_sh** | Float | Share of metropolitan employment  (within grid) located in this cell (same as psemph, just a fraction; added to facilitate input into GRID-toolkit) |

All data are from 2015. For a more detailed description of the data sources, see Ahlfeldt, Albers, Behrens (2025)

## Reference: 

## Reference: 

Ahlfeldt G., Albers T., Behrens K. (2024): Prime locations. American Economic Review: Insights, forthcoming.

Bondarenko M., Priyatikanto R., Tejedor-Garavito N., Zhang W., McKeen T., Cunningham A., Woods T., Hilton J., Cihan D., Nosatiuk B., Brinkhoff T., Tatem A., Sorichetta A.. Constrained estimates of 2015-2030 total number of people per grid square at a resolution of 3 arc (approximately 100m at the equator) R2025A version v1. Global Demographic Data Project - Funded by The Bill and Melinda Gates Foundation (INV-045237). WorldPop - School of Geography and Environmental Science, University of Southampton. DOI:10.5258/SOTON/WP00839
 
