# white-abalone-habitat-modeling
Data repository for white abalone habitat models (PLOS ONE 2021 publication)

## **Manuscript number**
PONE-D-20-33702

## **Manuscript DOI**

## **Article title**
Modeling the past, present, and future distributions of endangered white abalone (Haliotis sorenseni) to inform recovery efforts in California

## **Abstract**
White abalone (Haliotis sorenseni) was once commonly found in coastal waters of the Southern California Bight (SCB) and south to Punta Abreojos, Baja California, Mexico. During the 1970s, white abalone supported a commercial fishery, which remarkably reduced the population and resulted in the closure of the fishery in 1996. When population levels continued to decline, National Marine Fisheries Service (NMFS) listed the species as endangered under the Endangered Species Act. The California Department of Fish and Wildlife and NMFS began surveying the wild populations, propagating specimens in captivity, and protecting its seabed habitat. We modeled coarse-scale (17 x 17 km) historical (using fishery-dependent data [1955-1996]) and contemporary (using fishery-independent data [1996-2017]) distributions of white abalone throughout its historical domain using random forests and maximum entropy (MaxEnt), respectively, and its fine-scale (10 x 10 m) contemporary distribution (fishery-independent data) using MaxEnt. We also investigated potential outplanting habitat farther north under two scenarios of future climate conditions. The coarse-scale models identified potential regions to focus outplanting efforts within SCB while fine-scale models can inform population monitoring and outplanting activities in these particular areas. These models predict that areas north of Point Conception may become candidate outplant sites as seawater temperatures continue to rise in the future due to climate change. Collectively, these results provide guidance on the design and potential locations for experimental outplanting at such locations to ultimately improve methods and success of recovery efforts.


## **Coarse-scale environmental data**

### CDFW bathymetry data
### _Description_
CDFW-bathy file contains a shapefile representing seafloor elevation (m). 

### _References_
Shuman, C. (2009). Marine Region GIS Downloads: Bathymetry. California Department of Fish and Game: Marine Region.https://www.wildlife.ca.gov/Conservation/Marine/GIS/Downloads. 

### CalCOFI sea surface temperature data
### _Description_
CalCOFI-temp.csv contains surface temperature data collected at CalCOFI stations.

### _References_
NOAA SWFSC (2017). CalCOFI NOAAHydros. ERDDAP. https://coastwatch.pfeg.noaa.gov/erddap/tabledap/erdNOAAhydros.graph 

### Bio-ORACLE projected sea surface temperature data
### _Description_
Bio-ORACLE-projtemp file contains ASCIIs representing future sea surface temperature projections for 2050 and 2100 under each RCP scenario (RCP 2.6, RCP 4.5, RCP 6.0, and RCP 8.5)

### _References_
Bio-ORACLE (2017). Bio-ORACLE data. Bio-ORACLE. https://www.bio-oracle.org/downloads-to-email.php

Tyberghein L, Verbruggen H, Pauly K, Troupin C, Mineur F, De Clerck O (2012) Bio-ORACLE: A global environmental dataset for marine species distribution modelling. Global Ecology and Biogeography, 21, 272–281.

Assis, J., Tyberghein, L., Bosh, S., Verbruggen, H., Serrão, E. A., & De Clerck, O. (2017). Bio-ORACLE v2.0: Extending marine data layers for bioclimatic modelling. Global Ecology and Biogeography.


## **Fine-scale environmental data**

### CSUMB SFML bathymetry data
### _Description_
CSUMBSFML_bathy contains shapefiles representing seafloor elevation (m), slope (degrees), and vector ruggedness measure.

### _References_
CSUMB SFML (2008). SFML Data. CSUMB SFML. https://seafloor.otterlabs.org/SFMLwebDATA.htm

### SBC LTER kelp canopy area and biomass data
### _Description_
SBCLTER-kelp file contains netCDFs of kelp biomass used to derive kelp persistence and associated metadata. 

### _References_
Bell, T, Cavanaugh, K., Siegel, D. (2020). SBC LTER: Time series of quarterly NetCDF files of kelp biomass in the canopy from Landsat 5, 7 and 8, since 1984 (ongoing) ver 13. Environmental Data Initiative. https://doi.org/10.6073/pasta/5d3fb6fd293bd403a0714d870a4dd7d8.

### REEF white abalone competitors and predators abundance data
### _Description_
REEF-comppred file contains competitor and predator abundance score data used to derive indies of competitors abundance and predator diversity.

### _References_
REEF (2017). Reef Environmental Education Foundation Volunteer Fish Survey Project Database. World Wide Web electronic publication. https://www.reef.org


