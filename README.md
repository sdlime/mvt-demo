Simple demo for MapServer Mapbox Vector Tile (MVT) support using the Mapbox-GL library.

<img src="https://raw.githubusercontent.com/sdlime/mvt-demo/master/screenshot.png" width="350">

Setup:
<ol>
  <li> Install/compile https://github.com/sdlime/mapserver/tree/vector-tiles branch. Note that building MVT support requires protobuf and protobuf-c.</li>
  <li> Install the contents of this repo on your webserver someplace (e.g. /mvt-demo).</li>
  <li> Edit sample.json -> sources.compass.tiles property to reflect your setup:
  <ul>
    <li> URL for MapServer compiled with MVT support.</li>
    <li> Location of the demo.map file.</li>
  </ul></li>
  <li> Point your browser to the index.html file and if all went well you should see something like the above screenshot.</li>
</ol>
