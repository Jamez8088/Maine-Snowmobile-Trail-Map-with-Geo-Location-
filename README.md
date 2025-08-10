# Maine Snowmobile Trail Map with Geo-Location
Using the map layer publically available on Arcgis.com, then places a simple GPS locator icon on the map showing where you are with the majority of snowmobile trails in Maine, easy as that. 
This is in beta! I'm still working on adding some features and removing bugs, so expect some down time here and there.  
# Click the link below! Dont forget to enable location when prompted!!
Just go to https://jamez8088.github.io/Maine-Snowmobile-Trail-Map-with-Geo-Location-/index.html

[Features:]
- Realtime directional GPS tracking.
- Up-to-date trail map.
- Realtime weather forecasts and conditions.
- Offline map persistence.
- Current Points of Interest, like gas stations and lodging.
- GPS Route Planning (Planned)
- GPS Speedometer (Planned)

# Disclaimer and Patch Notes

- I do not own the rights to any of these map layers, all map layers are from ArcGIS which can be found here: 

Points: https://hub.arcgis.com/datasets/COAGIS::gps-trailmasters-snowmobile-pois/explore?layer=0&location=44.839697%2C-69.199815%2C12.75

Trails: https://hub.arcgis.com/datasets/COAGIS::gps-trailmasters-snowmobile-pois/explore?layer=2&location=45.208741%2C-68.925947%2C7.69

# Patch Notes:
[8/9/2025 - Ver. 0.3]
  - Updated the map version from 2015 to 2017.
      - A much more recent and dense version of the map, still not final but better.
      - [New version was extracted using raw JSON data from https://www.arcgis.com/sharing/rest/content/items/eafcdafee1134205b8b4abf10658d4db/data?f=json]
  - Added weather forcast system based on current ZIP code:
      - Provides realtime temperature in farenheit.
      - Provides current conditions.
      - Provides +12hr realtime forecasts.
  - Added customizable color selections for both the POI's and user arrow.
  - POI's are now semi-transparent circles.
  - POI's can also now be toggled on/off.


 
[8/8/2025 - Ver. 0.2] 
  - Changed user icon to a functional arrow.
  - Fixed CSS error causing overlapping buttons.
  - Embedded travel points, such as gas stations and lodging.
  - Fixed all trails being called "Trail" when being tapped or clicked on, they now show what they are such as ITS or Ice Crossings.
  - Added functional descriptors to travel points.
