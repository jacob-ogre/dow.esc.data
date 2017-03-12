# US Counties plus TIGER

_TopoJSON of all U.S. Counties and TIGER (2015) Data_

- [Metadata](#Metadata_11)
- [Description](#Description_25)
- [Variables](#Variables_38)
- [Applications](#Applications_47)
- [Archives](#Archives_53)
- [Comments](#Comments_60)

## Metadata
- **Version:** 1.0
- **Date:** 2015
- **SHA-256:** 
    - US_counties_TIGER.topojson: d539a08602b400e68e58369f0edce8b3ce04d3f40fbbdce7d54fc57fdb814cde
    - US_counties_attrib.tsv: C8914f29d7f38407566cb5a4391fc4a898c037cf9f652189e9820d38615ec0406
- **License:** CC-BY
- **Source:** 
    - The TopoJSON was created from the shapefiles in the 2015 [U.S. Census Bureau TIGER geodatabases](https://www.census.gov/geo/maps-data/data/tiger-geodatabases.html) using the [topojson tool](https://github.com/topojson/topojson). 
    - The counties attributes file was created by extrating tables from the shapefiles using [QGIS](http://www.qgis.org/). (I think.)

## Description

A pair of files for plotting county-level data. For efficiency and accuracy, 
each datapoint should be associated with the GEOID for JOINs.

## Variables

#### **US_counties_attrib.tsv**

- **STATEFP** = Two-digit state FIPS code
- **COUNTYFP** = Three-digit county FIPS code
- **COUNTYNS** = Another county-level code
- **GEOID** = Five-digit concatenated state, county FIPS code
- **NAME** = County name
- **NAMELSAD** = Long-form county (or other unit, e.g., Township) name
- **LSAD** = Unknown categorical variable
- **CLASSFP** = Unknown categorical variable
- **MTFCC** = Unknown categorical variable
- **CSAFP** = Unknown categorical variable
- **CBSAFP** = Unknown categorical variable
- **METDIVFP** = Unknown categorical variable
- **FUNCSTAT** = Unknown categorical variable
- **ALAND** = County land area (units unknown)
- **AWATER** = County water area (units unknown)
- **INTPTLAT** = County latitude centerpoint
- **INTPTLON** = County longitude centerpoint

## Applications

Web applications using these dataset include:

- [ESA expenditures](https://cci-dev.org/shiny/closed/ESA_expenditures_v0-3/)
- [ESA listings summary](https://cci-dev.org/shiny/open/listings-summary/)

## Archives

External public repositories containing these data sets:

- figshare: NA
- Zenodo: NA

## Comments

NA

[Top](#US_Counties_plus_TIGER_0)
