# Toolkit for Prime Locations (AABPL)
(c) Gabriel M. Ahlfeldt, Thilo N. H. Albers, Kristian Behrens
Version 1.0.0, 2025-01

## General description

This toolkit complements Ahlfeldt, Albers, Behrens (2024), who develop a delineation algorithm for ultra-dense employment clusters within cities, which is applied to US MSAs and a sample of Global Cities. 

This toolkit consists of the following main components:
- shapefiles of delineated prime locations for 381 US MSAs (all except Puerto Rico) and 125 Global cities
- data sets that provide key statistics on these prime locations and summarize the geography of prime locations by city
- shapefiles for micro-geographic grids that include employment by sector (US MSAs) as well as predicted employment and other measures of economic activity (Global Cities)
- An interactive toolkit that allows for a convenient visual impression of delineated prime locations and data download by city
- A Python version of our delineation algorithm which is flexibly applicable to spatial point pattern data

This toolkit is a complement and not a substitute for the replication directory. For reproduction of the results reported in the article, we refer to the official **replication directory** which is currently under construction.

When using the toolkit in your work, **please cite** Ahlfeldt, Albers, Behrens (2024): Prime locations, American Economic Review: Insights, forthcoming.

## Interactive toolkit

As a part of this toolkit, we provide an [interactive web tool](https://sites.google.com/view/ahlfeldt/toolkits-and-webtools/prime-locations) that conveniently presents our delineated prime locations against the background of the spatial distribution of economic activity for 381 US MSAs and 125 Global Cities.

## Algorithm

The **Python package** for the delineation of spatial clusters akin to prime locations is published in this [GitHub repository](https://github.com/Ahlfeldt/AABPL-toolkit-python). It uses arbitrary spatial point patterns as input and returns a gridded version of the data along with polygons of the delineated spatial clusters as outputs. 

## Data

All data outputs are available from the folders below. Outputs for individual cities can be conveniently downloaded using our [interactive web tool](https://sites.google.com/view/ahlfeldt/toolkits-and-webtools/prime-locations). To download the content as a whole, the most convenient way is to access the directory via [GitHub Desktop](https://github.com/apps/desktop)

Folder | File | Description |
|:---------------------------------------------|:---------------------------------------------|:-------------------------------------------------------------------------|
| [DATA/GlobalCities](https://github.com/Ahlfeldt/AABPL-toolkit/tree/main/DATA/GlobalCities) |  metro-data.csv | CSV file containing a summary of the geography of prime locations by Global City (Global City identifier; number of prime locations; percentage share of city employment in prime locations; percentage share of city area in prime locations; city name; type of city structure). |
| [DATA/GlobalCities](https://github.com/Ahlfeldt/AABPL-toolkit/tree/main/DATA/GlobalCities) |  PL-data.csv | CSV file key statistics of prime locations (prime location identifier; city name; Global City identifier;	employment rank of prime location within city; prime location area; share of prime location at city employment; share of prime location at city area). Merges to the shapefile in the shape_all.zip archive in folder [SHAPEFILES/GlobalCities](https://github.com/Ahlfeldt/AABPL-toolkit/tree/main/SHAPEFILES/GlobalCities) |
| [DATA/GlobalCities](https://github.com/Ahlfeldt/AABPL-toolkit/tree/main/DATA/GlobalCities) |  prime_points_weighted.zip | Zip archive containing CSV files with big data establishments (including predicted employment) for all Global Cities|
| [DATA/USMSAs](https://github.com/Ahlfeldt/AABPL-toolkit/tree/main/DATA/USMSAs) | metro-data.csv | CSV file containing a summary of the geography of prime locations by Global City (CBSA identifier; city name; number of prime locations;	percentage share of city area in prime locations; percentage share of city employment in prime locations; percentage share of manufacturing employment in prime locations;	percentage share of non-tradable services employment in prime locations;	percentage share of public services employment in prime locations;	percentage share of tradable services employment in prime locations;	percentage share of other employment in prime locations; MSA area; MSA employment;	type of city structure) |
| [DATA/USMSAs](https://github.com/Ahlfeldt/AABPL-toolkit/tree/main/DATA/USMSAs) |  PL-data.csv  |CSV file key statistics of prime locations (prime locations identifier;	CBSA identifier; city name; prime location rank in US; prime location rank within city; latitude; longitude; area; employment; employment density; percentage share of manufacturing employment in prime location; same for non-tradable services; same for public services; same for tradable services; same for other employment; MSA employment; indicator for satisfying minimum size; indicator for being largest prime location in city; share of manufacturing employment at total at total employment outside prime locations; same for non-tradable services; same for public services; same for tradable services; same for other employment; same for employment in establishments that correspond to our big data search terms). Merges to the shapefile in the shape_all.zip archive in folder [SHAPEFILES/USMSAs](https://github.com/Ahlfeldt/AABPL-toolkit/tree/main/SHAPEFILES/USMSAs).|
| [MAPS/GlobalCities](https://github.com/Ahlfeldt/AABPL-toolkit/tree/main/SHAPEFILES/GlobalCities) | GISMAP_PL_metroXXX.png | PNG map illustrating prime locations for a Global City, where XXX is the Global Cities identifier. These maps can also be conveniently viewed within an interactive drop-down menu [here](https://sites.google.com/view/ahlfeldt/toolkits-and-webtools/prime-locations/prime-locations-in-129-global-cities). |
| [MAPS/USMSAs](https://github.com/Ahlfeldt/AABPL-toolkit/tree/main/MAPS/USMSAs) | MAPS_PL_TotalEmp_BaseP_XXXXX.png|PNG map illustrating prime locations for a US MSA, where XXXXX is the CBSA identifier. These maps can also be conveniently viewed within an interactive drop-down menu [here](https://sites.google.com/view/ahlfeldt/toolkits-and-webtools/prime-locations/prime-locations-in-381-us-msas). |
| [SHAPEFILES/GlobalCities](https://github.com/Ahlfeldt/AABPL-toolkit/tree/main/SHAPEFILES/GlobalCities) | shape_all.zip | ZIP archives containing one shapefile of all prime locations in all Global Cities |
| [SHAPEFILES/GlobalCities](https://github.com/Ahlfeldt/AABPL-toolkit/tree/main/SHAPEFILES/GlobalCities) | shape_XXX.zip | ZIP archives containing one shapefile of prime locations in the Global City with identifier XXX. |
| [SHAPEFILES/GlobalCities](https://github.com/Ahlfeldt/AABPL-toolkit/tree/main/SHAPEFILES/GlobalCities) | grid_XXX.zip | ZIP archives containing one shapefile of a micro-geographic grid for the Global City with identifier XXX, with data on predicted employment and other markers of economic activity |
| [SHAPEFILES/USMSAs](https://github.com/Ahlfeldt/AABPL-toolkit/tree/main/SHAPEFILES/USMSAs) | shape_all.zip | ZIP archives containing one shapefile of all prime locations in all US MSAs|
| [SHAPEFILES/USMSAs](https://github.com/Ahlfeldt/AABPL-toolkit/tree/main/SHAPEFILES/USMSAs) | shape_XXXXX.zip | ZIP archives containing one shapefile of prime locations in the US MSA with CBSA identifier XXXXX. |
| [SHAPEFILES/USMSAs](https://github.com/Ahlfeldt/AABPL-toolkit/tree/main/SHAPEFILES/USMSAs) | grid_XXXXX.zip| ZIP archives containing one shapefile of a micro-geographic grid for the US MSA with CBSA identifier XXXXX, with data on employment by sector |

## Reference: 

Gabriel M. Ahlfeldt, Thilo N. H. Albers, Kristian Behrens (2024): Prime locations. American Economic Review: Insights, forthcoming.

## Acknowledgements
We thank [Max von Mylius](https://github.com/maximylius) for developing the Python version of our algorithm in this [GitHub repository](https://github.com/Ahlfeldt/AABPL-toolkit-python)
