# Latlong

Simple converter from DMS to decimal coordinates. Includes a small tool for
looking up airports by ICAO code.

### Running locally

Open `index.html` using a local web server (for example `python3 -m http.server`)
and ensure you have network access. If the remote airport database cannot be
loaded, the page will fall back to the bundled `data/airports.dat` file.
