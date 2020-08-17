# gpx-merger
Merge GPX files into a single one.

Take multitple GPX files (routes, waypoints, tracks) and merge them into a single one. For example, useful when you hit GMaps MyMaps layer number restriction and have many little routes.

`source .env/bin/activate ; pip install -r requirements.txt`

To launch:

`python3 GPXMerger.py -d <input directory> > <output file>`

`<input directory>` will contain all GPX files to be merged. 

`<output file>` will be the name of the resulting, merged file.

For example:

`python3 GPXMerger.py -d data/Route66AtlasWaypoints_GPX_Format > merged/route_66.gpx`

To create a heatmap, use [JOSM](https://josm.openstreetmap.de/).