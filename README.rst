IDR Searchengine Browser
--------------------------
This web application has a graphic user interface for working with
the OMERO search engine indexed with IDR data at https://idr.openmicroscopy.org/.

It was forked from an [experimental PR](https://github.com/ome/omero_search_engine_client/pull/25)
of https://github.com/ome/omero_search_engine_client.

* Filter IDR data using any combination of `AND` and `OR` conditions
* Group images from a Study by their metadata

The app is built using SvelteKit and is a static site

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
