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
| **pop** | Float | Total population of the cell (Gridded Population of the World) |
| **pop_sh** | Float | Cells's share of metropolitan population (within grid) located in this cell |

All data are from 2015. For a more detailed description of the data sources, see Ahlfeldt, Albers, Behrens (2025)

## Reference: 

Gabriel M. Ahlfeldt, Thilo N. H. Albers, Kristian Behrens (2024): Prime locations. American Economic Review: Insights, forthcoming.

