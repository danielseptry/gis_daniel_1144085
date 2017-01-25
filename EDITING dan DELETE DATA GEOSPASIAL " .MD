Background
We already know that the development of these technologies will be more advanced. So many ways that we use to bring new inventions that exist in this world, where the question is perkembanagan technology for the future. The discovery in question is one of which is a GIS. Given these findings it is very helpful in menyelesaika problem.
So it can be said that in the absence of progress, the system is useless. Therefore mutually support each other. Humans can communicate using jaringn
Given these developments, we will better understand the use of the system, because with this application can help in interaction so that communications made to run smoothly.
At the time we did the digitization, the results of delineation will appear on the computer monitor. Through a computer monitor, we'll know if something goes wrong. Therefore, it is necessary to do editing on the data that has been entered. Editing is a process to improve the outcome of digitization. Errors that often occur at the time of digitization is the overshoot and undershoot.

Discussion
Writer () is a method in shapefile to create a new shp file (shp and dbf)
Editor () function to perform editing on a shapefile
Example: delete record.
Script writter:
Ø Python
Ø Import shapefiles
Ø Sf = shapefile.writer (shapeType = 1)
Ø Sf = field ( 'NAME', 'C', '40')
Ø Sf = field ( 'OWNER', 'C', '40')
Ø Sf = record ( 'Warung Nasi', 'Asep Dinamo')
Ø Sf = point (10:10)
Ø Sf.save ( 'warteg.shp')
Ø Exit ().
Script Edit:
Ø Python
Ø Import shapefiles
Ø Sf = sahefile.Editor ( 'war.shp')
Ø Sf = point (16,10,0,0)
Ø Sf = record ( 'Padang')
Ø Sf = save ()
Ø Sf = save ( 'war.shp')
Ø A = shapefile.Reader ( 'war, shp')
Ø A = records ()
Ø A.shapes (). Points
Ø A.shapes () [0]
Ø A.shapes () [0] Points
[[10.0,10,0]]

Delete Script:
Ø Sf.Delete (0)
Ø A.shapes () [0] .Points
[[10,0,10,0]]
Ø Sf = Point (16,10,0,0)
Ø Sf = record ( 'Padang')
Ø Sf = save ( 'war.shp')
Conclusion
From the discussion above, we can draw conclusions with their GIS, the communications made by man can walk with their GIS, GIS buffer is also used for business so that we jalanka business will go well. Let us take the example that one company, then pads discussion this time we can use the way - the way shapefile to determine areas with remote
Suggestion
For better better future, look referansi complete and easy to understand so that many can science and bermanfaan.
Google Terjemahan untuk Bisnis:Perangkat PenerjemahPenerjemah Situs Web

NAMA : DANIEL PANJAITAN
KELAS : D4 TI 3D
NPM : 1144085
