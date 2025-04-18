# License
This data was generated using data from the Redistricting Data Hub.  Any use of this project shall also comply with restrictions on use of data and attribution requirements set forth in the Redistricting Data Hub terms and conditions found at: [https://redistrictingdatahub.org/terms-and-conditions/](https://redistrictingdatahub.org/terms-and-conditions/).

Use of this project is further governed by the terms of the [Creative Commons Attribution Noncommercial 4.0 International](https://creativecommons.org/licenses/by-nc/4.0/legalcode.en)

# Colorado Election Json

This shapefile was processed by Professor Ellen Veomett and her student Arbie Hsu using the corresponding jupyter notebook.  As part of the cleaning process, small rook adjacencies (under 30.5 m) were changed to queen adjacencies.  We did *not* nest precincts inside of counties, as that resulted in an error (which we believe will be able to be fixed with the next maup update).

# **Sources**

The following obtained from [Redistricting Data Hub](https://redistrictingdatahub.org/) on June, 2024:

[Population data](https://redistrictingdatahub.org/dataset/colorado-block-pl-94171-2020-by-table/): based on the decennial census at the Census Block level on 2020 Census Redistricting Data

[Congressional District data](https://redistrictingdatahub.org/dataset/2021-colorado-final-approved-congressional-plan/): 2022 Congressional Districts Approved Interim Plan

[State House District data](https://redistrictingdatahub.org/dataset/2021-colorado-final-approved-state-house-map/): 2022 State House Approved Interim Plan

[State Senate District data](https://redistrictingdatahub.org/dataset/2021-co-final-approved-sldu-plan/): 2022 State Senate Districts Interim Plan from

[2020 election data](https://redistrictingdatahub.org/dataset/vest-2020-colorado-precinct-boundaries-and-election-results-shapefile/): VEST 2020 precinct and election results

[2018 election data](https://redistrictingdatahub.org/dataset/vest-2018-colorado-precinct-and-election-results/): VEST 2018 precinct and election results 

[2016 election data](https://redistrictingdatahub.org/dataset/vest-2016-colorado-precinct-and-election-results/): VEST 2016 precinct and election results

[2020 County data](https://redistrictingdatahub.org/dataset/colorado-county-pl-94171-2020/): from 2020 Census Redistricting Data (P.L. 94-171) Shapefiles

# **Processing**

Data were cleaned and aggregated in the corresponding jupyter notebook using MGGG’s python library [maup](https://github.com/mggg/maup).

# **Metadata**

Below is a brief description of each of the listed variables in the attribute table of the VTD shapefile:

- `STATEFP20`: State FIPS code
- `COUNTYFP20`: County FIPS code
- `PRECINCT20`: Precinct identifier based on precinct of 2020
- `VTDST20`: Voting tabulation district FIPS code
- `NAME20`: Voting tabulation district name of 2020
- `CD`: Congressional district ID in 2021 enacted congressional map
- `SEND`: State Senate district for 2021 State Senate Adopted Plan
- `HDIST`: State House district for 2021 State House of Representatives Districts Plan
- `TOTPOP`: Total population in 2020 Census
- `NH_WHITE`: White, non-hispanic, population in 2020 Census
- `NH_BLACK`: Black, non-hispanic, population in 2020 Census
- `NH_AMIN`: American Indian and Alaska Native, non-hispanic, population in 2020 Census
- `NH_ASIAN`: Asian, non-hispanic, population in 2020 Census
- `NH_NHPI`: Native Hawaiian and Pacific Islander, non-hispanic, population in 2020 Census
- `NH_OTHER`: Other race, non-hispanic, population in 2020 Census
- `NH_2MORE`: Two or more races, non-hispanic, population in 2020 Census
- `HISP`: Hispanic population in 2020 Census
- `H_WHITE`: White, hispanic, population in 2020 Census
- `H_BLACK`: Black, hispanic, population in 2020 Census
- `H_AMIN`: American Indian and Alaska Native, hispanic, population in 2020 Census
- `H_ASIAN`: Asian, hispanic, population in 2020 Census
- `H_NHPI`: Native Hawaiian and Pacific Islander, hispanic, population in 2020 Census
- `H_OTHER`: Other race, hispanic, population in 2020 Census
- `H_2MORE`: Two or more races, hispanic, population in 2020 Census
- `VAP`: Total voting age population in 2020 Census
- `HVAP`: Hispanic voting age population in 2020 Census
- `WVAP`: White, non-hispanic, voting age population in 2020 Census
- `BVAP`: Black, non-hispanic, voting age population in 2020 Census
- `AMINVAP`: American Indian and Alaska Native, non-hispanic, voting age population in 2020 Census
- `ASIANVAP`: Asian, non-hispanic, voting age population in 2020 Census
- `NHPIVAP`: Native Hawaiian and Pacific Islander, non-hispanic, voting age population in 2020 Census
- `OTHERVAP`: Other race, non-hispanic, voting age population in 2020 Census
- `2MOREVAP`: Two or more races, non-hispanic, voting age population in 2020 Census
- `ATG18D`: Number of votes for 2018 Democratic attorney general candidate
- `ATG18R`: Number of votes for 2018 Republican attorney general candidate
- `ATG18O`: Number of votes for 2018 other party's attorney general candidate
- `GOV18D`: Number of votes for 2018 Democratic gubernatorial candidate
- `GOV18R`: Number of votes for 2018 Republican gubernatorial candidate
- `GOV18O`: Number of votes for 2018 other party's gubernatorial candidate
- `PRE16D`: Number of votes for 2016 Democratic President
- `PRE16O`: Number of votes for 2016 other party's  President
- `PRE16R`: Number of votes for 2016 Republican President
- `PRE20D`: Number of votes for 2020 Democratic President
- `PRE20R`: Number of votes for 2020 Republican President
- `RGT16D`: Number of votes for 2016 Democratic State University Regent
- `RGT16R`: Number of votes for 2016 Republican State University Regent
- `RGT18D`: Number of votes for 2018 Democratic State University Regent
- `RGT18R`: Number of votes for 2018 Republican State University Regent
- `RGT18O`: Number of votes for 2018 other party's State University Regent
- `SOS18D`: Number of votes for 2018 Democratic Secretary of State
- `SOS18R`: Number of votes for 2018 Republican Secretary of State
- `SOS18O`: Number of votes for 2018 other party's Secretary of State
- `TRE18D`: Number of votes for 2018 Democratic Treasurer
- `TRE18O`: Number of votes for 2018 Republican Treasurer
- `TRE18R`: Number of votes for 2018 other party's Treasurer
- `USS16D`: Number of votes for 2016 Democratic senate candidate
- `USS16R`: Number of votes for 2016 Republican senate candidate
- `USS16O`: Number of votes for 2016 other party's senate candidate
- `USS20D`: Number of votes for 2020 Democratic senate candidate
- `USS20R`: Number of votes for 2020 Republican senate candidate
- `USS20O`: Number of votes for 2020 other party's senate candidate
