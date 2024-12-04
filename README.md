# !!! This toolkit is under construction !!!

# Toolkit for Prime Locations (AABPL)
(c) Gabriel M. Ahlfeldt, Thilo N. H. Albers, Kristian Behrens
Version 1.0.0, 2024-10

## General description

This toolkit complements Ahlfeldt, Albers, Behrens (2024), who develop a delineation algorithm for ultra-dense employment clusters within cities which is applied to US MSAs and a sample of Global Cities. This toolkit contains shapefiles of delineated prime locations for all US MSAs and the sampled Global cities, data sets that provide key statistics on these prime locations and summarize the geography of prime locations by city, as well as a Python version of the delineation algorithm which is flexibly applicable to spatial point pattern data.

When using the toolkit in your work, please cite Ahlfeldt, Albers, Behrens (2024).

## Repository contents
### Folders

Name | Description |
|:---------------------------------------------|:-------------------------------------------------------------------------|
| [AGLORITHM](https://github.com/Ahlfeldt/AABPL-toolkit/tree/main/ALGORITHM) | Python version of the delineation algorithm that can be applied to spatial point pattern data with a user-friendly syntax.   |
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

Gabriel M. Ahlfeldt, Thilo N. H. Albers, Kristian Behrens (2024): Prime locations.
