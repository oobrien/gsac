# Local Internet Content

_These files, description and metadata were downloaded from the CDRC Data Service website on 6 December 2024 and are republished under the UK Open Government Licence (OGL)._

Local Internet Content (LIC) is a methodology (see Python function workbook below) and map to record the volume and reach of archived online content of local interest at the Middle Super Output Level (MSOA) for England and Intermediate Geography (IG) for Scotland. The data used for the map is based on the UK Web Archive and utilises entries of the JISC UK Web Domain Dataset, which is a subset of the Internet Archive and curated by the British Library and includes all the archived webpages under the .uk top level domain, contains a timestamp, the URL of the archived website as well as the British postcode found on each site.

The methodology and dataset can be used to derive a measure for how much local internet content (LIC) exists across the UK and estimate a ‘Radius of Gyration’ (RG) for the geographic reach of websites. This measure refers to a computation of the mean distance between a websites’ set of postcodes (p) by performing the steps in the workbook on the coordinate data.

### Additional Info

| Field |	Value |
| --- | --- |
| DOI | 10.20390/localinternetcontent |
| Attribution | Created by Emmanouil Tranos and Christoph Stich. Data provided by the Consumer Data Research Centre, an ESRC Data Investment: ES/L011840/1, ES/L011891/1 |
| Topic | Digital |
| Tags | Internet |
| Source | JISC UK Web Domain Dataset |
| Extent | United Kingdom |
| Licence | UK Open Government Licence (OGL) |

### Files

| Filename | Title | Description |
| --- | --- | --- |
| lic2001.csv | Local Internet Content 2001-10 (2001 Boundaries)
| lic2011.csv | Local Internet Content 2011-12 (2011 Boundaries)
| licall_crude.csv | Local Internet Content 2001-12 (Using 2011 Boundaries with Crude Mapping to 2004 Boundary Values) | This combined file uses the 2011 MSOA geographies for England/Wales. The LIC data for 2001-10 is based on the 2001 boundaries, where these vary from 2011, a crude fitting has been applied. This results in a small loss of data and a small amount of duplication from the original published dataset, affecting around 2% of areas. For Scotland, no fitting was required as the LIC data for all years was mapped on the 2001 boundaries. |
| Local Internet Content.ipynb | Calculating Local Internet Content (Python Function / Jupyter Notebook) | This notebook details how to calculate the Local Internet Content (LIC) for an arbitrary dataset of geolocated websites. For a detailed explanation see: Tranos, E., & Stich, C. (2020). Individual internet usage and the availability of online content of local interest: A multilevel approach. Computers, Environment and Urban Systems, 79, 101371. |
| licdescription.pdf | Local Internet Content - Description |

### Related Content

| Name | URL |
| --- | --- |
| Mapmaker map of the Local Internet Content data (based on licall_crude.csv) | https://mapmaker.geods.ac.uk/#/local-internet-content |
| UK Web Archive | https://www.webarchive.org.uk/ |
| JISC and the Internet Archive (2013) | JISC UK Web Domain Dataset (1996-2013). The British Library. https://doi.org/10.5259/ukwa.ds.2/1 |
| Tranos, Emmanouil & Stich, Chrisotph. (2020) | Individual internet usage and the availability of online content of local interest: A multilevel approach. Computers, Environment and Urban Systems. 79. 101371. https://doi.org/10.1016/j.compenvurbsys.2019.101371 |
