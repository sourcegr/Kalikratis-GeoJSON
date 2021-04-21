# Kallikratis municipalities of Greece in GeoJSON

Each one of the `*.js` files contained in the `datafiles` directory exports a `data` with the corresponding GeoJSON data for each municipality. The naming scheme is the YPES Code for each municipality.

The reference system is the WGS84.

The names of the regions are included in the `ypesCodeMapping.json` file.

All data were retrieved from the geodata.gov.gr website.

## How to use the files in google maps

Just add the GeoJSON data from the file you want in the data layer of the map object

```js
map.data.addGeoJson(data);
```
where map is the map you created.


## Licence

[CC By 3.0](https://creativecommons.org/licenses/by/3.0/)

