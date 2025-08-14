# Maine Snowmobile Trail Map with GPS and Weather
Using some map layers publically available on Arcgis.com, then places a simple GPS locator icon on the map showing where you are with the majority of snowmobile trails in Maine, simple as that. 
This is in beta! I'm still working on adding some features and removing bugs, so expect some down time here and there.  
# Click the link below! Dont forget to enable location when prompted!!
Just go to https://jamez8088.github.io/Maine-Snowmobile-Trail-Map-with-Geo-Location-/index.html

[Features:]
- Realtime directional GPS tracking with Follow.
- Color-Customizable user and POI icons.
- Up-to-date trail map.
- Realtime weather forecasts and conditions.
- Offline map persistence.
- Current Points of Interest, like gas stations and lodging. (More to come)
- GPS Route Planning (Planned)
- GPS Speedometer (Planned)

# Disclaimer and Patch Notes

- I do not own the rights to any of these map layers, all map layers are from ArcGIS which can be found here: 

Points: https://hub.arcgis.com/datasets/COAGIS::gps-trailmasters-snowmobile-pois/explore?layer=0&location=44.839697%2C-69.199815%2C12.75

Trails: https://hub.arcgis.com/datasets/COAGIS::gps-trailmasters-snowmobile-pois/explore?layer=2&location=45.208741%2C-68.925947%2C7.69

# Patch Notes:
[8/11/2025 - Ver. 0.3.4]
- Added Size Settings button to main UI.
     - Size sliders for:
        - Arrow Size.
        - Points Size.
        - Trail Size (visual width).

[8/10/2025 - Ver. 0.3.3]
- Manually traced some new/club trails, highlighted in blue. More will be coming soon.
- Shrunk down all button sizes.
   - Increased the variable size parameters to better suit mobile devices.
- Added Hide Settings/Show Settings button to the bottom right to show and hide all context buttons.
- Added zoom slider while follow is on for fixed zoom control. 

[8/9/2025 - Ver. 0.3]
  - Updated the map version from 2015 to 2017.
      - A much more recent and dense version of the map, still not final but better.
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
