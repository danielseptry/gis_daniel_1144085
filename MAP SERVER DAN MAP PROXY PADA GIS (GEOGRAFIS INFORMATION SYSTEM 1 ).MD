Background
Information on the geographical increasingly required by many parties, such as the distance information between the regions, locations, facilities, natural resources are looking for, and lots of other information. The information is needed users for various purposes such as research., Development and regional planning, and the management of natural resources. Only the deployment of spatial data that has been done using existing media covering the print media / maps, CD-ROMs and other storage media is lacking sufficient for the user because the user is required to come and view the data directly in place. This reduces the mobility and speed in obtaining information about the data.
GIS or SIG marupakan known as one of the solutions to mrndapatkan information that geography. When this has been known terms - terms Desktop GIS, WebGIS, and Spatial Dtaabase that reflects the development of GIS technology.
Map Server is one of the programs CGI (Common Gateway Interface) which can be used to build web-based GIS applications. Map Server provides several features that are required for the management of a map, for example, increase or decrease the size of the scale of the map, the processing of information relating to a location and more
Discussion
Map Server
Map Server is to transform into a vector file shp geospatial web service image.
How instlasi:
Here practice meggunakan Centos 6.8. for Windows users simply can meggunakan VirtualBox.
VirtualBox:
1. Setting parameter 1 GB ram and hard drive to taste (defauld 8 GB).
2. Setting the IP in a way to edit the file ifcfg-etho
The syntax is as follows:
#vi / etc / sysconfig / network - scripts / ifcfg - etho
Change ONBOOT be yes.
3. Perform installation folder server dependencies.
To add a repository, then perintahya are as follows:
#rpm - uuh http: //dounload.fedora project.org / puh / Epel / 6 / x86 - 64 / Epel - release - 6.8.noarch.rpm.
#rpm - uuh http://ellis.argeo.org / repost / 6 / elgis - release - 6-6 - 0.noard.rpm
#wget http://elgis.orgeo.org / repos / 6 / elgis / x86 - 64 / gdal - 1.9.2.-4.el 6.x86 - 64.rpm
4. Exclude armadillo dar repo Epel, with the following command:
#vi / etc / /etc/yum.repos.d / epel.repo
Adding: Exclude = armadillo * after the line gpg key.
5. Installation armadillo
# yum install -3.800.2-2.elb armadillo. x86 - 64.rpm
6. Continue the installation depondensi:
# yum install GPSBabel
# yum install gdal
# yum install MapServer
# yum install glibc
# yum install libpng libpng- devel
# yum install gd gd-devel
# yum install giflib-devel
# yum install proj-devel
7. completed, check the installation path;
# Rpm-gl MapServer.
Installation Folder Proxy
Proxy Folders is an application to create temperoray images on the client does not request directly to the server folder so performasi better.
How to Install:
# yum install python-pip python-devel
#pip install folder proxy
# Mapproxy-util create-T base-config anu

If you've finished the installation, then try Undu map of Indonesia and the Config folder proxy files and folders in the menu gis with the website address is www.halaman.dounload.

Conclusion:
There are some of the conclusions drawn after completing this task is as follows:
1. Map Server can both be used to build web-based GIS applications are interactive.
2. Map Server can facilitate access spatial data in real time.
Suggestion:
There are some criticisms and suggestions that need to be delivered, with the hope will be a useful input, namely:
1. MapServer application development with menggunkaa bahsas scripts such as PHP / Mapscript or Javascript in order to facilitate user interaction.
2. The existence of a support facilities / equipment needed in the process of making GIS will help produce a more accurate GIS.
3. Addition dibutuhakan features such as the addition of raster data, searching function and tool tips.

NAMA : DANIEL SEPTRY PANJAITAN
KELAS : D4 TI 3D
NPM : 1144085
