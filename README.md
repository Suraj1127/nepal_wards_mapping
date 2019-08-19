# Ward Level Administrative Mapping
###### Work done by Nepal Poverty Team, The World Bank

## Overview

In the last few decades, Nepal has seen major political and structural changes of which federalism is the one. The process of splitting and merging of VDC/municipality wards has been going even before the federalism era but once federalism was introduced the structuring became totally different than what it was. From around 4000 VDC/municipalities, the merging/splitting process resulted in around 3300 VDC/municipalities before the federal structuring was done. Once federal structuring was done, the new level, Local Unit (LU), was introduced which consisted of wards. Ward is the lowest level of new federal structure. As of now, there are 775 LUs (including designated areas too) and around 6800 wards of which detailed data per province (in GIS map) is given [here](http://103.69.124.141/). It is to be noted that the GIS map does not account for designated areas (national parks, wildlife reserves, conservation area, hunting reserve).

The World Bank, Nepal Country Office, has produced ward-wise mappings from the old structure to new federal structure for its internal use and has made the mapping public in GitHub. There are two separate mappings, one from 2011 structure to 2018 federal structure and another from 2014 structure to 2018 federal structure.

## Mappings

For the mappings, we have used HLCIT_CODE, codes for local units introduced by High Level Commission for Information Technology (HLCIT), as HLCIT codes are available for all the 775 units whereas CBS codes, introduced by Central Bureau of Statistics (CBS), are available for only 753 units (have not included designated areas). 
### old_wards_2011_to_new_wards_2018.csv
It contains the mapping at the ward level from 2011 structure to 2018 post-federalism structure.

The columns *ZONE*, *OLD_DISTRICT_NAME*, *OLD_VDCMUN_NAME*, *OLD_WARD_NO*, *OLD_HLCIT_VDC_CODE* and *OLD_HLCIT_WARD_CODE* represent the administrative structure information for 2011. The columns *PROVINCE*, *NEW_DISTRICT_NAME*, *NEW_HLCIT_DISTRICT_CODE*, *NEW_LU_FULL_NAME*, *LU_TYPE*, *NEW_LU_NAME*, *NEW_HLCIT_LU_CODE*, *NEW_WARD* and *NEW_HLCIT_WARD_CODE* represent the administrative structure information for 2018.

### old_wards_2014_to_new_wards_2018.csv
In 2014 too, there was administrative re-structuring for some of the VDCs/municipalities though not due to federalism. 
Therefore, We have produced mapping for 2014 structure too.

It contains the mapping at the ward level from 2014 structure to 2018 post-federalism structure.

The columns, *District*, *VDC/Municipality Name*, *OLD_WARD_NO*,
represent the administrative structure information for 2014. The corresponding columns, *Province*, *District Code*, *Category of LU*, *LU Name*, *LU Name CBS*, *LU Name Nepali*, *LU HLCIT Code*, *LU CBS Code*, *NEW_WARD_NO* and *LU CBS Ward Code*,
represent the administrative structure information for 2018.