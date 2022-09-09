This page details two datasets:

* Residential Population Density with Urban/Rural Classification
* Workplace Population Density 

## Residential Population Density with Urban/Rural Classification

The ruralurban dataset combines the most recently available small-area population density and urban/rural
classification information available from the three UK national statistics agencies - ONS/NOMIS (2011,
England/Wales), NRS (2011 and 2013-4, Scotland) and NISRA/NINIS (2011 and 2015-6, Northern Ireland).

Because the three agencies use slightly different ways of creating their urban/rural classifications, a
bespoke unified classification is created by combining them. 

Analysts should note that, while ONS considers
"City and Town in a Sparse Setting" (C2) to be Urban, it is treated as Rural (R2) in the unified classification,
because the unified classification makes an equivalence between "remote" and "sparse" population areas
and does not consider either to be urban, regardless of settlement population size. Therefore, analysts
should use the source classifications rather than the unified one, when seeking to extract a simple official
Urban vs Rural statistic. For convenience, this is included in the lookup file.

Key | Value 
---|---
Date Range|2011-15
Collecting Date|2013-16
Data Collector|ONS (England/Wales), NRS (Scotland), NISRA (Northern Ireland)
Geographical Scales|Output Area
Analytical Units|Person
Bounding box|United Kingdom
Source URL|https://www.gov.uk/government/statistics/2011-rural-urban-classification-of-local-authority-and-other-higher-level-geographies-for-statistical-purposes https://www.nomisweb.co.uk/census/2011/qs102ew http://www.gov.scot/Publications/2014/11/2763/2 http://www.scotlandscensus.gov.uk/ods-web/data-warehouse.html http://www.nisra.gov.uk/geography/UrbanRural.htm http://www.ninis2.nisra.gov.uk/public/Theme.aspx?themeNumber=74&themeName=Population
Source|ONS (England/Wales), NRS (Scotland), NISRA (Northern Ireland)
Publication Year|2016
Geography URL|https://geoportal.statistics.gov.uk/
CDRC Map URL|https://maps.cdrc.ac.uk/#/metrics/ruralurban/

## Workplace Population Density 

The workplace population dataset is a merge of the NOMIS (England & Wales) and NRS (Scotland) Workplace Population Density files
from the 2011 Census. The original records are at https://www.nomisweb.co.uk/census/2011/wp102ew
(https://www.nomisweb.co.uk/census/2011/wp102ew) and https://www.scotlandscensus.gov.uk/odsweb/data-warehouse.html#additionaltab (https://www.scotlandscensus.gov.uk/ods-web/datawarehouse.html#additionaltab).

A geofile for the UK (i.e. including NI) is also included. However, as NI has not released population counts
for its workplace zones, these are not included in the datafile.

Key | Value 
---|---
Date Range | 2011
Collecting Date | 27/03/11
Data Collector | ONS
Geographical Scales | Workplace Zone
Analytical Units | Person
Bounding box | Great Britain
Source URL | https://www.nomisweb.co.uk/api/v01/dataset/nm_155_1.bulk.csv?time=latest&measures=20100&geography=TYPE262
Attribution Statement | Please check the linked NOMIS pages for attribution
information.
CDRC Map URL | https://maps.cdrc.ac.uk/#/metrics/workplacepop/
