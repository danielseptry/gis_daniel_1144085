Background
Geographic Information System is a system that has been designed to be used for handling data that has space so that it can be said GIS can also combine the data to get the highest output that can be used with a reference to decide the geographical problem. In this GIS terdpat two systems of systems that are still manual and automated system that already has a different function. But now the GIS used are already automated GIS to manage data. So that the data that is managed effectively and efficiently.
GIS applications can be used for various purposes for the data to be an object which has a physical shape and location. Therefore, the Geographic Information System is intended to facilitate in obtaining the information that has been processed and stored as an attribute in the site or onjek. The data can be processed that data in the form of spatial data, which spatial data is data that is related to the spatial locations are generally shaped map. So the presentation of spatial data is divided into 3 points, poliline, and polygons. And also the spatial data structure is divided into two, namely the data model raster and vector data model
Discussion
Retrieve geospatial data
So we will take the ESRI shapefile vector geospatial data. As we know shapefile divided into 2dbf and shp.dbf is table data attributes. Shp is the geometry data. Where the geometry data from ESRI standard geeometri namely Point, Poliline, Polygon. That point is in the form of points, poliline is a line and polygon is in the form of the area is the meeting between the starting point to the end point, it can be said jugabahwa polygon is the starting point = end point.
 Well it is a vector geospatial data or standard shapefile ESRI.Operasi in python, the python kit mengenalada pyshp library, from the library pyshp we call by way of import shapefiles. Istansiasi class shapefile to a variable sf = shapefile.Reader ( 'bts.negara.shp). sf is istansiasi, shapefile is a class, Reader is a method, ( 'bts.negara.shp) is fileshp parameter. So here is istansi variable sf of class shapefile, we can run the method in the variable sf. Suppose we use the agency sf then divided into two, namely that method and shp dbf. Method dbf if we make use sf agencies that can use data attributes.
Dbf data attributes are divided into 3 parts:
1. sf.fields can be used to view the attribute table.
2. sf.records () can be used to retrieve all the records
3. sf.record (n) used to take the line to the nth record
Shp data attributes are divided into 3 parts:
1. sf.shapes () is used to retrieve all the records geometry data.
2. sf.shape (n) can be used to record megambil nth row.
How to access object data was biased view the Dir (a) that there are several parts:
1. BBOX also called bonding box which point the outskirts of maps, eg maps Indonesia are point pingiran a, b, c, and d that is called the bonding box where the map can be seen by a rectangle.
2. Parts is whether the record is part of another record but rarely used.
3. Points are coordinates forming shapetype.
4. Shapetype is the standard geometry data from ESRI.
How to access is a variable should be stored in advance, namely:
a.box
a.shapetype
a.poits

At the geospatial data can select the shapefile by using looping. Suppose Indonesia sf.for a search for data in sf.records (): has an algorithm which takes the data all in one iteration.



Data retrieval operations in Python
The amount of data read geometry:
>> Import shapefile
>> Sf = shapefile.Reader ( "namafile.shp")
>> Sf.shapes ()
>> A = sf.shapes ()
>> Len (a)

The amount of data read Geometry:
>> Import shapefile
>> Sf.records ()
>> Sf.records (n)
Conclusion
Retrive geospatial data is one of the ways used to facilitate and accelerate the search data (data retrieval). So that the processed data in GIS is basically composed of spatial data and attribute data in digital form, thus the analysis that can be used is the analysis of spatial and attribute analysis. Spatial data is data related to the spatial locations which generally have shaped the map. While the attribute data is the data table that serves to explain the existence of various objects as spatial data.

NAMA : DANIEL PANJAITAN
KELAS : D4 TI 3D
NPM : 1144085
