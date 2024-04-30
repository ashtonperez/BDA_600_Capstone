# Unvailing Food Deserts in San Diego

[Website](https://sites.google.com/sdsu.edu/unveiling-food-deserts-in-san-/home)

[Project Video](https://youtu.be/9q7gJ6TRbf0)

This research project is the work from SDSU's BDA 600 Capstone Course. Our research highlights key characteristics and vulnerable populations in San Diego food desert tracts.

## Orginal Sources

1. https://www.ers.usda.gov/data-products/food-access-research-atlas/download-the-data/
2. https://www2.census.gov/geo/tiger/GENZ2010/gz_2010_06_140_00_500k.zip

** Note for GIS Users: The Atlas is based on 2010 census tract polygons. To use the underlying Atlas data in a GIS, the data from this spreadsheet needs to be joined to a census tract boundary file. 

Pay special attention to the file name: where 2010 is year, 06 is for California fips code, 140 for the summary level code of State-County-Census Tract. These codes are called out in thel readme in the same directory: https://www2.census.gov/geo/tiger/GENZ2010/ReadMe.pdf 

The file gz_2010_06_140_00_500k.dbf inside the zip is a DBF file that can actually be opened in Excel. The columns B,C,D makeup the CensusTract primary key that can be used to join to the other Atlas dataset.i
