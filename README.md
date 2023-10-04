# Globalpraxtix code challenge 

¡Welcome to this project related to ETL with data! Here you can find all the info that you need to know

## Goal

The goal of this problem is to obtain the average income per person for each of the operating zones based on the publicly available information from the National Institute of Statistics (INE), which allows us to know the income level for each of the different census sections in Spain.

## Inputs 
To carry out this test, in the folder you will find the following files:
- atlas_socioeconomico: in this file you will obtain the necessary income information to solve the problem posed. It is at the city, neighborhood and census section aggregation level.
- census_zones_ine: in this file you will find in geojson format the representation of the multiple census sections of Spain.
In addition, they contain the following codes as information:
- CUSEC: unique census section identifier (composed of the aggregation of the following metrics in red)
- CSEC: code only for the census tract
- DCIS: census tract code only
- CUMUN: municipality code only
- CPRO: province code only
- CCA: code of the autonomous community
- Other metrics: NUTS standard codes, name of the Municipality, etc.
- poblacion_sec_censal: population of all census sections of the province of Barcelona identified by their unique census section identifier.
- operator_zones: geojson with the operator zones. The following metric is relevant:
• Index: unique identifier of the zone.

## Output


The expected output is:
- Excel/csv: with the following columns:
-- Index: obtained directly from the operator_zones file
-- Average income per person.
- Notebook with the code commented.


