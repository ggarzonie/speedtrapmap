# speedtrapmap
Script that maps areas where drivers are most likely to get pulled over by Texas Highway Patrol for speeding

This uses kernel density estimation of traffic stops and linear interpolation over traffic volume to generate a score for likeliness to get pulled over. The 97th percentile of roads with >5000 estimated AADT are plotted.

Here are the sources of data
Mile markers: https://gis-txdot.opendata.arcgis.com/maps/txdot-reference-markers
Traffic volume: https://gis-txdot.opendata.arcgis.com/datasets/txdot-aadt-annuals
Traffic stops: https://www.dps.texas.gov/section/highway-patrol/texas-highway-patrol-high-value-data-sets
