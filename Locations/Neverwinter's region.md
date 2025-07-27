---
tags:
  - location
date: 26-04-2025
map: true
owner: 
---
# Map

```leaflet
id: region-map
image: [[004-map-0.01-phandalin-region-player.webp]]
width: 100%
height: 750px
lat: 51
long: 47
minZoom: 9
maxZoom: 12
defaultZoom: 10
unit: meters
scale: 1
```


# Quests


```dataview
LIST
FROM #quest 
WHERE destination-loc = this.file.name
```

# Information