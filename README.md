# Mexico Geographic Data (CSV)

This repository contains CSV files with geographic information of Mexico.
The data is intended to be used for seeding databases in development projects.

Files included

* country.csv – Country list (includes Mexico and optionally other countries)
* states.csv – States of Mexico
* municipality.csv – Municipalities of Mexico
* locality.csv - Localities of Mexico (~8MB)
* sepomex.csv – Complete Postal Codes dataset (SEPOMEX), converted into a single CSV file (~16MB)


Each file can easily be related to other files via their columns.

## Usage

Clone or download this repository (or copy the individual CSV files).
In your main project, place the files where you need them.


## Source

* SEPOMEX Postal Codes: Official dataset published by the Government of Mexico.
* States and Municipalities: INEGI and other public datasets.


## Notes

* sepomex.csv has been normalized and merged into a single sheet for easier import.
* The original sepomex data can be [downloaded here](https://www.correosdemexico.gob.mx/SSLServicios/ConsultaCP/CodigoPostal_Exportar.aspx).
* The original Localities file can be [downloaded here](http://www.dgis.salud.gob.mx/contenidos/intercambio/localidades_gobmx.html).
* Here is the original [Countries GIST](https://gist.github.com/brenes/1095110).
* For the original Mexico States and Municipalities can be downloaded on [INEGI ageeml](https://www.inegi.org.mx/app/ageeml/) as CSV files with more information.
