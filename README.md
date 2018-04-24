# GeoPortal v3

[GeoPortal](https://mcmap.org/geoportal) is a *one stop shopping for location information* app. It weighs ~400KB on desktop, ~250KB on mobile, and it's now a Progressive Web App! 

![Imgur](http://i.imgur.com/vhpOqNj.png)

Created by Mecklenburg County GIS, with much ♥ for the projects that make this site possible: OpenStreetMap, OpenMapTiles, Mapbox GL JS, Vue.js, and Material Design Lite

Yarn must be installed to build. To Install:

```bash
brew install yarn
```


## Getting started

```bash
git clone https://github.com/wilsongis/Montgomery-County-GeoPortal.git geoportal
cd geoportal
npm install
npm run build
npm start
```

To build the app for deployment (service worker precache, uglify JS, minimize CSS and images, etc.), run the build again:

``` bash
npm run build
```
