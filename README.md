## Tiny Tina's Wonderlands Interactive Map
https://soulbulb.github.io/tiny-tinas-wonderlands-imap/

The Tiny Tina's Wonderlands Interactive Map is a single page web application that displays *most* of the collectibles in every map.

The mapping library used is [Leaflet](https://leafletjs.com/). The points are stored as GeoJSON files with one file corresponding to each layer. Each GeoJSON feature has a property called *imgname* that stores the location of the screenshot that corresponds to that point.

I created this single page application specifically to be stored and used on Github to save on hosting costs. This does unfortunately mean that there is some performance issues at times with rendering the basemap. If I were to create a similar application for enterprise use I would serve the basemap as WMS tiles and the data as WFS tiles from a Geoserver instance with Postgres for data storage.

This Website was created by the GTA V Interactive Map Template from 
* **Jesse Gardner** - *Template Creator* - [Github](https://github.com/jgardner117)

## To Do:
* Capture additional additional data to add to each point
* Add Boss Locations and special Secrets
* Create screenshots for all points
* Potentially create Geoserver instance to serve tiles and WFS to improve loading times

## Authors
* **Soulbulb** - *Creator* - [Github](https://github.com/soulbulb)


## Acknowledgements/Copyright information
Tiny Tina's Wonderlands and all associated references, images, etc. &copy; [Gearbox Software](https://www.gearboxsoftware.com)

Icons &copy; [Icons8](https://icons8.com/)

Screenshots from [Gameclubz](https://www.gameclubz.com)
