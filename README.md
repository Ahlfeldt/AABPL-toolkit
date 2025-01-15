# !!! This toolkit is under construction !!!

# Toolkit for Prime Locations (AABPL)
(c) Gabriel M. Ahlfeldt, Thilo N. H. Albers, Kristian Behrens
Version 1.0.0, 2024-10

## General description

This toolkit complements Ahlfeldt, Albers, Behrens (2024), who develop a delineation algorithm for ultra-dense employment clusters within cities which is applied to US MSAs and a sample of Global Cities. 

This toolkit consists of the following main ingredients:
- shapefiles of delineated prime locations for 381 US MSAs (all except Puerto Rico) and 125 Global cities
- data sets that provide key statistics on these prime locations and summarize the geography of prime locations by city
- Micro-geographic grids that include employment by sector (US MSAs) as well as predicted employment and other measures of economic activity (Global Cities
- An interactive toolkit that allows for a convenient visual impression of delineated prime locations and data download by city
- A Python version of our delineation algorithm which is flexibly applicable to spatial point pattern data

This toolkit is a complement and not a substitute for the replication directory. For reproduction of the results reported in the article, we refer to the official replication directory which is currently under construction.

When using the toolkit in your work, please cite Ahlfeldt, Albers, Behrens (2024): Prime locations, American Economic Review: Insights, forthcoming.

## Interactive toolkit

As a part of this toolkit, we provide an [**interactive web tool**](https://sites.google.com/view/ahlfeldt/toolkits-and-webtools/prime-locations) that conveniently presents our delineated prime locations against the background of the spatial distribution of economic activity for 381 US MSAs and 125 Global Cities.

## Aglorithm

The **Python package** for the delination of spatial clusters akin to prime locations is available form this sister [GitHub repository](https://github.com/Ahlfeldt/AABPL-toolkit-python). It uses arbitrary spatial point patterns as input and returns a gridded version of the data along with polygons of the delineated spatial clusters as outputs. 

## Data

All data outputs are available from the folders below. Since these folders contain many files, the most convenient way of accessing the content is to access the directory via [GitHub Desktop](https://github.com/apps/desktop)

Name | Description |
|:---------------------------------------------|:-------------------------------------------------------------------------|
| [DATA/GlobalCities](https://github.com/Ahlfeldt/AABPL-toolkit/tree/main/DATA/GlobalCities) | Folder containing data sets that provide key statistics of prime locations (merges to a shape file in [SHAPEFILES/GlobalCities](https://github.com/Ahlfeldt/AABPL-toolkit/tree/main/SHAPEFILES/GlobalCities)) as well as a summary of the geography of prime locations by Global City. |
| [DATA/USMSAs](https://github.com/Ahlfeldt/AABPL-toolkit/tree/main/DATA/USMSAs) | Folder containing data sets that provide key statistics of prime locations (merges to a shape file in [SHAPEFILES/USMSAs](https://github.com/Ahlfeldt/AABPL-toolkit/tree/main/SHAPEFILES/USMSAs)) as well as a summary of the geography of prime locations by USMSA.|
| [MAPS/GlobalCities](https://github.com/Ahlfeldt/AABPL-toolkit/tree/main/SHAPEFILES/GlobalCities) | Folder containing maps of prime locations by Global City. These maps can also be conveniently viewed within an interactive drop-down menu [here](https://sites.google.com/view/ahlfeldt/toolkits-and-webtools/prime-locations/prime-locations-in-129-global-cities). |
| [MAPS/USMSAs](https://github.com/Ahlfeldt/AABPL-toolkit/tree/main/MAPS/USMSAs) | Folder containing maps of prime locations by Global City. These maps can also be conveniently viewed within an interactive drop-down menu [here](https://sites.google.com/view/ahlfeldt/toolkits-and-webtools/prime-locations/prime-locations-in-381-us-msas). |
| [SHAPEFILES/GlobalCities](https://github.com/Ahlfeldt/AABPL-toolkit/tree/main/SHAPEFILES/GlobalCities) | Folder containing separate shapefiles for prime prime locations for each Global City and one shapefile containing all prime locations in all Global Cities.  |
| [SHAPEFILES/USMSAs](https://github.com/Ahlfeldt/AABPL-toolkit/tree/main/SHAPEFILES/USMSAs) | Folder containing separate shapefiles for prime prime locations for each MSA and one shapefile containing all prime locations in all MSAs.  |

### Selected Files

Folder | Name  | Description |
|:-------------------|:-------------------------------------|:-------------------------------------------------------------------------|
| [-](https://github.com/Ahlfeldt/ABRSQOL-toolkit) | `AABPL-Codebook.pdf` | **Codebook** laying out the **structure of the deliniation algorithm in pseduo code** |


## Reference: 

Gabriel M. Ahlfeldt, Thilo N. H. Albers, Kristian Behrens (2024): Prime locations. American Economic Review: Insights, forthcoming.
