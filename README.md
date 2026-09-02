# Ireland_2022_for_ERA
.dbf file to be used with the Electoral Redistricting App / ERA

Electoral Redistricting App available at https://era.idea.int/#/ and https://github.com/InternationalIDEA/ERA

Most recent compatible shapefile available @ https://www.cso.ie/en/census/census2011reports/census2011boundaryfiles/ (Electoral Divisions Zip file) <br>
or download backup from Internet Archive @ https://web.archive.org/web/20240718162941/https://www.cso.ie/en/media/csoie/census/census2011boundaryfiles/Electoral_Divisions.zip

Then recompress "Proper Names" subfolder with the attached .dbf file rather than the existing one in the folder

The new file adds a 2022 population column (based on: https://data.cso.ie/table/F1060 ) matching data as closely as possible to the 2011 map (main discrepancy being being the 2019 Cork City boundary change but also some very low population EDs are combined differently between the censuses)

Loading the full file into ERA can lag a lot, so use an app like QGIS to filter down using the County or NUTS attributes 
<br>Remember to export filtered map with Coordinate Reference System (CRS) set to EPSG:4326 (WGS84)
<br>https://qgis.org/download/
<br>https://mapscaping.com/filtering-in-qgis-a-comprehensive-guide/
