# gmaps-radius-for-drone-planning
Simple web app that allows you to draw circles on top of a Google Map, with a specified radius and colour.

Tool originally created by Oliver Beattie https://github.com/obeattie, Twitter @obeattie.

## Google Maps API Key ##
You will need a Google Maps API Key.
https://developers.google.com/maps/documentation/embed/get-api-key

## Map Options ##
- `Map`: with Terrain tickbox
- `Satellite`: with Labels tickbox

## URL Parameters ##
This tool supports the following URL query parameters:
- `lat`: viewport center latitude
- `lng`: viewport center longitude
- `z`: default zoom level
- `r`: default circle radius
- `u`: default circle radius unit

Units available:
- `mi`: Miles
- `km`: Kilometers
- `ft`: Feet
- `mt`: Metres
- `in`: Inches
- `yd`: Yards
- `fa`: Fathoms
- `na`: Nautical Miles
- `ch`: Chains
- `rd`: Rods
- `fr`: Furlongs

URL Example:
`index.html?r=50&u=mt`: will load a default setting of 50 metres

Controls:
- `Mouse Left Click`: Create circle
- `Mouse Right Click`: Delete circle
