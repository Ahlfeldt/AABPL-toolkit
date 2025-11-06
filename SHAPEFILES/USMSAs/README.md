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
| **pop_dens** | Float | Cell's population density (persons per km², from gridded population of the world)  |
| **pop_sh** | Float | Cells's share of metropolitan population (within grid) located in this cell |
| **emp_sh** | Float | Share of metropolitan employment  (within grid) located in this cell (same as psemph, just a fraction; added to facilitate input into GRID-toolkit) |

For a more detailed description of the data sources, see Ahlfeldt, Albers, Behrens (2025)

## Reference: 

Gabriel M. Ahlfeldt, Thilo N. H. Albers, Kristian Behrens (2024): Prime locations. American Economic Review: Insights, forthcoming.

