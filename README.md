# README

A tiny, quick and dirty demo using [tinysearch](https://github.com/tinysearch/tinysearch/tree/master) to create a geocoder using wasm for city level search in the browser

We could optimize this to be smaller, but for now it loads ~6mb of data into the browser, takes about 10ms

Demo adpated from the `wasm_output` of https://github.com/tinysearch/tinysearch?tab=readme-ov-file#usage

## Data
* derived from https://simplemaps.com/data/world-cities 

## Links to: 
* geojson.io


## run it locally

```
python3 -m http.server
```