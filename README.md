# Mapping_Earthquakes

Files for a page displaying a map of tectonic plates and all earthquakes across the globe from the past 7 days. Earthquakes are displayed as circles base on their coordinates with relative size equal to their magnitude times 4. Sepearte overlays for all earthquakes, all major earthquakes (magnitude > 4.5), and the tectonic plates are included along with options to view the data on a street map, sattelite map, or dark map.

### Usage

You can run the code yourself in Google Chrome using a local override provided you have your own API key from MapBox. 

To set up Local Overrides:

1. Open the Sources panel.
2. Open the Overrides tab.
3. Click Setup Overrides.
4. Select which directory you want to save your changes to.
5. At the top of your viewport, click Allow to give DevTools read and write access to the directory.
6. Using the developer console for your browser (ctrl+shift+i in Chrome), replace "API_KEY" in the javascript file with your key.

### Example snapshot from 11/26/2021

![11-26-2021-earthquake-map](https://github.com/deklund76/Mapping_Earthquakes/blob/main/Resources/11-26-21.jpg)

Data courtesy of USGS.
