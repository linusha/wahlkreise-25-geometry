# Geometry of Germany's Wahlkreise for the 2025 Federal Elections

GeoJSON obtained by converting the official shapefiles provided by the [Bundeswahlleiterin](https://www.bundeswahlleiterin.de/bundestagswahlen/2025/wahlkreiseinteilung/downloads.html).

## Properties

For each "Wahlkreis"-Path, the following attributes are available inside of its properties object:

- `WKR_NR` -	Number of Wahlkreis
- `WKR_NAME` -	Name of Wahlkreis
- `LAND_NR` -	Number of German Sate
- `LAND_NAME` -	Name of German State 

## Demo App

For demonstration purposes, a simple test application (largely provided by ChatGPT) that shows the name of each Wahlkreis on hover is included.

You might need a simple HTTP server to run this locally, such as [`http-server`](https://www.npmjs.com/package/http-server).


## License

© Die Bundeswahlleiterin, Statistisches Bundesamt, Wiesbaden 2024,
Wahlkreiskarte für die Wahl zum 21. Deutschen Bundestag
Grundlage der Geoinformationen © Geobasis-DE / BKG 2024
