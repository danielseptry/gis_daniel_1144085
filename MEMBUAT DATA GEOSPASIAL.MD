Background
We already know a file shapefile is a file that contains data about the layout of the earth, shapefile itself has supplied many examples such as those provided by ESRI but we do not know how to create shapefiles itself, by because it is here we will review how to make these shapefiles.
Discussion
Creating a Geospatial Data
Step - step in making geospatial data is as follows:
Import shapefiles
a = shapefile.writer ()
The data format goespasial No 2 is shp and dbf:
1. Shp = a.point (x, y)
a.poly [[x, y], [v, w]]
      2. dbf = a.field ( 'name.field,' c ',' 40 ')
                        a.record ( 'Bdg')
 This command means that we create an attribute table named the city with tipedatavarchar with a length of 40 characters, and if you want to add data, it can be done with the command:
      Record ( 'Bandung')
a.save stored using method ( 'file.shp') method in the sense of writer.
- Point (x, y) is entering data into a form point shp, and all data must be ESRI format
- Poly ([a, b], [c, d]) is a polygon-shaped memasukka geospatial data (back to point early) or poliline (not back to the starting point)
- Field ( 'name', 'c', '40') means to create an attribute table with 'name' to long varchar data type 40.
This method can be repeated continue to happen to the new file again
- Record ( 'Bandung') is to fill the table with just one file value = Bandung.
- Save ( 'filename') is to save the file save file.
Conclusion
By using python we can not only read the shapefile that has been provided, but we also create a shapefile Dapa itself.

NAMA : DANIEL PANJAITAN
KELAS : D4 TI 3D
NPM : 1144085
