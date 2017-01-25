
1379/5000
Background
Map Proxy is an open source proxy for geospatial data. These caches accelerate and transform data from existing map services and serves any desktop or web GIS client.
Discussion
Problems and Solutions Problems
Map function to perform caching proxy so that all the requests are not forwarded directly to the server folder. This is done so the importance of maintaining the performance load maps are not too long. Installation steps:

# Yummy install python-pip python-devel
# Pip install MapProxy

Create a folder proxy config file directory / var / mapproxy
# Cd / var /

mapproxy needs dbutuhkan yan open port 8080 on the iptables firewall os or by using the command
# Iptables -I INPUT -p tcp -j ACCEPT --dport 8080
# Service iptables save

How to pass MapProxy configuration, namely:
1. Create a folder MapData in / var on drektori create a new directory with the name shp, mapfile, tmp and common
2. Smpan vector file shapefile map didirektori / VAW / MapData / shp (sample province map file)
3. Edit the file /var/mymapproxy/mapproxy.yml adapted to record configuration
4. Then run the command mapproxy
# Mapproxy-util-develop mapproxy.yml serve -b 0.0.0.0

Conclusion
Proxy folder is open for this GIS data

Suggestion
You should always held practice every week to allow students to be more aware of the geographical information system materials

NAMA : DANIEL SEPTRY PANJAITAN
KELAS : D4 TI 3D
NPM : 1144085
