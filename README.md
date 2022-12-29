# microsoft-road-data

Microsoft recently made their mined road dataset free to download and use under the ODbL license. <br><br>
Using AI, they have detected road networks throughout the world.<br><br>
The data can be downloaded through [this link](https://github.com/microsoft/RoadDetections/?url=) and more information can be found in [this blog](https://blogs.bing.com/maps/2022-12/Bing-Maps-is-bringing-new-roads).  <br><br>
However, the data released is in TSV format, which is difficult to read in GIS softwares. 

<br><br>
The above jupyter notebook contains python script that reads the TSV file and converts it into two popular formats (geojson and geopackage) for GIS softwares. 
