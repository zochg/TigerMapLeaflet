# Tiger Map (Lab 4)

### WMS and WFS data

WMS url: http://localhost:8080/geoserver/cite/wms?service=WMS&version=1.1.0&request=GetMap&layers=cite:ore_counties&styles=&bbox=-124.56670504390223,41.991794810535794,-116.46326242572455,46.23731681568611&width=768&height=402&srs=EPSG:404000&format=image%2Fpng

WFS url: http://localhost:8080/geoserver/cite/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=cite:ore_counties&maxFeatures=50&outputFormat=application%2Fjson"



### Mapbox Basemap

Github URL: <https://zochg.github.io/TigerMapLeaflet/index.html

##### Design Process

I wanted to build a basemap based on my experiences studying in Thailand at a government nature preserve designated as a tiger habitat. As such, the maps's default position is centered above the preserve: Huai Kha Khaeng Wildlife Sanctuary. The icon for national parks has been changed to a paw to reflect the focus of conversation -- the tiger. The color scheme was based on the photo included in the screenshot folder. Using Coolor, I chose three major colors: orange, black, and green. Shades of brown underscore smaller features. The base layer is orange, representing the tiger's distinctive color. I chose to show the rivers, borders, and major roads as black to emphasize the black stripes on the tiger's coat. I chose green to show National Park overlays as I felt their shape frequently mirrored leaves and foliage that a tiger would move through -- leaves hide the tiger and so the green parks cover and conceal the orange base layer beneath. I used brown color tones for buildings at smaller scales to emphasize the dirt and leaves that end up on a tiger's coat.

