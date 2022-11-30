## Help

**geojson.io** is a quick, simple tool for creating, viewing, and sharing maps. geojson.io is named after [GeoJSON](http://geojson.org/), an open source spatial data format, and it supports GeoJSON in all ways - but also accepts KML, GPX, CSV, GTFS, TopoJSON, and other formats.

Want to request a feature or report a bug? [Open an issue on geojson.io's issue tracker.](https://github.com/mapbox/geojson.io/issues?state=open)

### I've got data

If you have data, like a KML, GeoJSON, or CSV file, just drag & drop it onto the page or click 'Open' and select your file. Your data should appear on the map!

### I want to draw features

Use the drawing tools to draw points, polygons, lines, rectangles, and circles. After you're done drawing the shapes, you can add information to each feature by clicking on it, editing the feature's properties, and clicking 'Save'.

Note: Circles are not supported in GeoJSON, so the circle drawing tool is really creating a circle-shaped polygon with 64 vertices.

Properties in GeoJSON are stored as 'key value pairs' - so, for instance, if you wanted to add a name to each feature, type 'name' in the first table field, and the name of the feature in the second.

### I'm a coder

[geojson.io accepts URL parameters](#geojson-io-api) that make it easy to go from a GeoJSON file on your computer to geojson.io.

### Privacy & License Issues

*   **The data you create and modify in geojson.io** doesn't acquire any additional license: if it's secret and copyrighted, it will remain that way - it doesn't have to be public or open source.