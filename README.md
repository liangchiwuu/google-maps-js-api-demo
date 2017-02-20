# google-maps-js-api-demo

## Overview

This is a simple website that demonstrates the following Google Maps JavaScript APIs:

1. Google Simple Polyline
2. Google Shortest Path
3. Google Heatmap

To demonstrate the corresponding function, simply select the function at the top, enter the latitude/longitude value for Start/End Position (or use default), then click "Draw" button. You can always clear the map by click "Clear" button.

* For the Simple Polyline function, this HTML will draw a simple polyline from Start Position to End Position user entered.
* For the Shortest Path function, this HTML will give a shortest route from Start Position to End Position user entered.
* For the Heatmap function, this HTML will randomly generate 100 coordinates in a square limited by the Start Position & End Position user entered.

The boundary and scale of the map will be automatically adjusted based on Start/End Position.

## Boundary Check

This HTML will check if the latitude is between +90 and -90; and also if the longitude is between +180 and -180. If the input data goes out of bounds, an error message will pop out to prompt user the correct range. 

## The University of Arizona

This HTML will put an "A" logo at the University of Arizona when loaded. Click the marker will give you more information about this school.

## License

GNU General Public License 3.0
