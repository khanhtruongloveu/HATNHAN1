Based on Mike Bostock’s [World Map][0], modified to automatically colour
countries such that no adjacent countries share the same colour.

This is done by extracting the topology via [TopoJSON][1] and greedily picking
colours until the constraint is fulfilled.

See also: [Graph coloring][2] on Wikipedia.

[0]: http://bl.ocks.org/4180634
[1]: https://github.com/mbostock/topojson
[2]: http://en.wikipedia.org/wiki/Graph_coloring
