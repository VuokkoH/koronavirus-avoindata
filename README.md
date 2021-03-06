# Health care district polygons in Finland

This repository contains two Jupyter Notebooks:
1. Workflow for **creating health district polygons**: [create_health_district_polygons.ipynb](create_health_district_polygons.ipynb)
2. Example of **how to join COVID-19 data to the health district layer**: [explore_covid_data.ipynb](explore_covid_data.ipynb) 

This repository was forked from [the Helsingin Sanomat datadesk](https://github.com/HS-Datadesk/koronavirus-avoindata) which I spotted on [Twitter](https://twitter.com/EsaMakinen/status/1237007961853173761). Please note that the example COVID-19 dataset in this repository is outdated (from 9 MARCH 2020).

## View and download health care district GIS layers

- [healthDistrictsEPSG4326.geojson](healthDistrictsEPSG4326.geojson) (WGS 84; click to view in bowser)
- [healthDistrictsEPSG3067.geojson](healthDistrictsEPSG3067.geojson) (ETRS89 / TM35FIN; download file and open, for example, in QGIS)

There is also a [csv file containing population per health care district on 31.12.2018](healtCareDistricts_population_31_12_2018.csv) based on information from Statistics Finland.
 
The health care district polygons and population information are based on [data from Statistics Finland](https://www.stat.fi/org/avoindata/paikkatietoaineistot/vaesto_tilastointialueittain.html) and a [list of health care districts by municipality from Kuntaliitto](https://www.kuntaliitto.fi/sosiaali-ja-terveysasiat/sairaanhoitopiirien-jasenkunnat). See the [Jupyter notebook](create_health_district_polygons.ipynb) for processing steps. 

Please use materials in this repository at your own discretion (no warranty that they are correct or up-to-date), and give credit to Statistics Finland for the data.

## Copyright information for the COVID-19 data: MIT-licence

Copyright 2020 Helsingin Sanomat

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
