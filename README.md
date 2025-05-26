# Cleaning the shorebird survey data 


## The original data set

ARCTIC SHOREBIRD DEMOGRAPHICS NETWORK [https://doi.org/10.18739/A2222R68W](https://doi.org/10.18739/A2222R68W)

Data set hosted by the [NSF Arctic Data Center](https://arcticdata.io) data repository 

Field data on shorebird ecology and environmental conditions were collected from 1993-2014 at 16 field sites in Alaska, Canada, and Russia.

![Shorebird, copyright NYT](https://static01.nyt.com/images/2017/09/10/nyregion/10NATURE1/10NATURE1-superJumbo.jpg?quality=75&auto=webp)

Data were not collected every year at all sites. Studies of the population ecology of these birds included nest-monitoring to determine the timing of reproduction and reproductive success; live capture of birds to collect blood samples, feathers, and fecal samples for investigations of population structure and pathogens; banding of birds to determine annual survival rates; resighting of color-banded birds to determine space use and site fidelity; and use of light-sensitive geolocators to investigate migratory movements. 

Data on climatic conditions, prey abundance, and predators were also collected. Environmental data included weather stations that recorded daily climatic conditions, surveys of seasonal snowmelt, weekly sampling of terrestrial and aquatic invertebrates that are prey of shorebirds, live trapping of small mammals (alternate prey for shorebird predators), and daily counts of potential predators (jaegers, falcons, foxes). Detailed field methods for each year are available in the `ASDN_protocol_201X.pdf` files. All research was conducted under permits from relevant federal, state, and university authorities.

See `01_ASDN_Readme.txt` provided in the [course data repository](https://github.com/UCSB-Library-Research-Data-Services/bren-meds213-spring-2024-class-data) for full metadata information about this data set.

### DATA and FILE OVERVIEW

File List:

- bren-meds213-data-cleaning.rproj <- R Project for this data cleaning exercise
- eds213_data_cleaning_assign_RYANGREEN.qmd <- Quarto Document for the data cleaning

- Data Folder
  
  processed <- Cleaned and Processed Data

  raw <- Original Data

- Docs Folder <- Rendered Quarto Document Files

_______

DATA-SPECIFIC INFORMATION FOR:

For the file  data/processed/all_cover_fixed_RYANGREEN.csv : 

11 Variables, 4,269 Rows

Variable List: 

- Site <- Abbreviation for Site Name
- Year <- Year the Observation was Collected
- Date <- Date the Observation was Collected
- Plot <- Plot the Observation was Collected
- Location <- Location the Observation was Collected
- Snow_cover <- Percent Snow Cover at Observation Location/Plot
- Water_cover <- Percent Water Cover at Observation Location/Plot
- Land_cover <- Percent Land Cover at Observation Location/Plot
- Total_cover <- Total Cover
- Observer <- Abbreviated Name of Observer
- Notes

Missing Data Code : NA
_______

SHARING/ACCESS INFORMATION

License : Creative Commons Attribution 4.0 International License


