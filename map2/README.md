# Welcome to the Map 2 in Zhen Liu's blog! 
There are four maps in this website. There are four different map layers in this website.

Output 1 consists of a leaflet map;

Output 2 consists of vector tiles with Mapbox;

Output 3 consists of a mark with popup on the map;

Output 4 consists of a map with customized color choices.

Here are some feature:
1. The color choices for the whole webpage is derived from the [venezuela-refugee-and-migrant-crisis](https://www.iom.int/venezuela-refugee-and-migrant-crisis). The background color of the top bar is #0033a1. When sub-page is chosen, the backgroung of the item will be changed to #0074bd. The color of the title is #0033a1, too. The color is detected by the tool in the Paint application in evryone's computer. After getting the RGB for the color, I convert it to hex color code by [google](https://www.google.com/search?q=color+picker). After that, I change the color of each part in css file.
2. In output 1, there are two layers which can be shown on the map. One is the openstreet map. The other is [Stamen map](https://stamen.com/). User can change the basemap by using the tile button on top right.
4. In output 4. The map color choices is derived from the website [IDP map](https://mangomap.com/idp-webmap/maps/94886/IDP-WEBMAP#). The color is extracted by the software Instant Eyedropper. The color of water is #D4DADB; the color of administratice border is #EBD6D8.
