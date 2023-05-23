# natres

This repository contains data relevant to India's annual natural resource (coal, oil, natural gas, non-fossil fuel minerals and forest resources) [rents](https://github.com/vinamrsachdeva/natres#rent-or-resource-rent) from 1971 to 2021 curated and estimated using several World Bank datasets. To understand how I estimated all values in the dataset, you can look at [this spreadsheet](https://docs.google.com/spreadsheets/d/1-Mwd9Yjtlltwksodfiiu61RiXPQXot29MHr7BBSr_Hk/).

{Forest to be added}

## Datasets

1. Total natural resource rents: [TOTAL_NATURAL_RESOURCE_RENTS.csv](https://github.com/vinamrsachdeva/natres/blob/main/datasets/TOTAL_NATURAL_RESOURCE_RENTS.csv)
2. Fossil-fuel (coal, oil and natural gas) rents: [FOSSIL_FUEL_RENTS.csv](https://github.com/vinamrsachdeva/natres/blob/main/datasets/FOSSIL_FUEL_RENTS.csv)
3. Coal rents: [COAL_RENTS.csv](https://github.com/vinamrsachdeva/natres/blob/main/datasets/COAL_RENTS.csv)
4. Oil rents: [OIL_RENTS.csv](https://github.com/vinamrsachdeva/natres/blob/main/datasets/OIL_RENTS.csv)
5. Natural gas rents: [NATGAS_RENTS.csv](https://github.com/vinamrsachdeva/natres/blob/main/datasets/NATGAS_RENTS.csv)
6. Non-fossil fuel mineral rents: [NON_FOSSIL_FUEL_MINERALS_RENTS.csv](https://github.com/vinamrsachdeva/natres/blob/main/datasets/NON_FOSSIL_FUEL_MINERALS_RENTS.csv)
7. Forest rents: [FOREST_RENTS.csv](https://github.com/vinamrsachdeva/natres/blob/main/datasets/FOREST_RENTS.csv)
8. Mineral (coal, oil, natural gas and non-fossil fuel minerals) rents: [MINERAL_RENTS.csv](https://github.com/vinamrsachdeva/natres/blob/main/datasets/MINERAL_RENTS.csv)

## Definitions
#### Rent or Resource rent
Sale price minus costs (provided costs include a "reasonable" return on capital invested).

#### Non-fossil fuel minerals rents
The [resource rents](https://github.com/vinamrsachdeva/natres#rent-or-resource-rent) from mining copper, gold, iron ore, lead, nickle, silve, and zinc according to World Bank's "[The Changing Wealth of Nations 2021: Managing Assets for the Future](http://hdl.handle.net/10986/36400)" report but resource rents from mining tin, gold, lead, zinc, iron, copper, nickel, silver, bauxite, and phosphate according to [the page on their website](https://data.worldbank.org/indicator/NY.GDP.MINR.RT.ZS?locations=IN) where the data has been taken from. Hence, [NON_FOSSIL_FUEL_MINERALS_RENTS.csv](https://github.com/vinamrsachdeva/natres/blob/main/datasets/NON_FOSSIL_FUEL_MINERALS_RENTS.csv) is the only dataset where there is some confusion; for the rest, World Bank's publications are consistent.

## Sources
1. Total natural resource rents (as % of GDP): [World Bank](https://data.worldbank.org/indicator/NY.GDP.TOTL.RT.ZS?locations=IN)
2. Coal rents (as % of GDP): [World Bank](https://data.worldbank.org/indicator/NY.GDP.COAL.RT.ZS?locations=IN)
3. Oil rents (as % of GDP): [World Bank](https://data.worldbank.org/indicator/NY.GDP.PETR.RT.ZS?locations=IN)
4. Natural gas rents (as % of GDP): [World Bank](https://data.worldbank.org/indicator/NY.GDP.NGAS.RT.ZS?locations=IN)
5. Non-fossil fuel minerals rents rents (as % of GDP): [World Bank](https://data.worldbank.org/indicator/NY.GDP.MINR.RT.ZS?locations=IN)
6. Forest rents (as % of GDP): [World Bank](https://data.worldbank.org/indicator/NY.GDP.FRST.RT.ZS?locations=IN)
7. GDP (current USD): [World Bank](https://data.worldbank.org/indicator/NY.GDP.MKTP.CD?locations=IN)
8. Official exchange rate (INR per USD): [World Bank](https://data.worldbank.org/indicator/PA.NUS.FCRF?locations=IN)
9. Population: [World Bank](https://data.worldbank.org/indicator/SP.POP.TOTL?locations=IN)
10. Inflation, consumer prices (annual %): [World Bank](https://data.worldbank.org/indicator/FP.CPI.TOTL.ZG?locations=IN)

World Bank on the sources they used to estimate the rents in their report, "[The Changing Wealth of Nations 2021: Managing Assets for the Future](http://hdl.handle.net/10986/36400)" (TABLE A.6 contains the revelant text):

![World Bank Sources](https://github.com/vinamrsachdeva/minerals/blob/main/wb_sources.png)
