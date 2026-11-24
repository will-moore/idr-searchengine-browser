IDR Searchengine Browser
--------------------------
This web application has a graphic user interface for working with
the OMERO search engine indexed with IDR data at https://idr.openmicroscopy.org/.

The app is deployed at https://will-moore.github.io/idr-searchengine-browser/.

It was forked from an [experimental PR](https://github.com/ome/omero_search_engine_client/pull/25)
of https://github.com/ome/omero_search_engine_client.

* Filter IDR data using any combination of `AND` and `OR` conditions
* Group images from a Study by their metadata

Some of the filtering and grouping behaviour was inspired by [BioFile Finder](https://bff.allencell.org/).

Screenshot shows filtering of IDR data by `Gene Symbol` equals `pax6` or `pax3` or `pax7` AND `Organism` equals `homo sapiens`. 
The `idr0043` Human Protein Atlas study is selected and the images are grouped by
`Organism Part` and `Gene Symbol`.

<img src="https://private-user-images.githubusercontent.com/900055/717356367-a876ec1a-ca01-4cc6-bfbc-55e86a8d8d69.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3OTU1MjY5MzUsIm5iZiI6MTc5NTUyNjYzNSwicGF0aCI6Ii85MDAwNTUvNzE3MzU2MzY3LWE4NzZlYzFhLWNhMDEtNGNjNi1iZmJjLTU1ZTg2YThkOGQ2OS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYxMTI0JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MTEyNFQxMzIzNTVaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT04NTdhODliY2EzYzkxNjcwNzQ0NTI5MDAwNzk1NmQ2NjNhMzY5OTVkYTFjNjljYzk2NTk5MTQxNDM5M2Y4MGE0JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZyZXNwb25zZS1jb250ZW50LXR5cGU9aW1hZ2UlMkZwbmcifQ.Fx-J0rMoCScLzcPAv7FKMg8hRE2kwYY5K_Vv_zpAiXA" />



The app is built using SvelteKit and is a static site.

Deploy preview
--------------

The `main` branch is deployed at https://will-moore.github.io/idr-searchengine-browser/

The gh-pages deployment was set-up with help from https://github.com/metonym/sveltekit-gh-pages/tree/master

Development
-----------

```
cd idr-searchengine-browser
npm install
npm run dev
```
