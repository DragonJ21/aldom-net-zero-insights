This repository contains four CSV files with data displayed in the BITRE Congestion Report. The file containing route parameters can be found at the github repository at github.com/bitre-telematics/congestion.

The four files are:
1. route_metrics.csv: Containing summary data on each route, with the fields
  route_name - name of route in report
  min median travel time - the lowest median travel time (by hour) for the route
  max median travel time - the highest median traveltime (by hour) for the route
  Peak time to best ratio - The ratio of longest to shortest median time
  min iq travel time - the interquartile (IQ) range width for the hour in which is was most narrow
  max iq travel time - the interquartile range width for the hour in which is was most wide
  Peak iq to best ratio - the ratio of the widest to most narrow IQ ranges
  min median travel hour - the hour of day (from 0 to 23) when median travel times were least
  max median travel hour - the hour of day (from 0 to 23) when median travel times were greatest
  min iq travel hour - the hour of day for which the IQ range was narrowest
  max iq travel hour - the hour of day for which the IQ range was greatest
  total obvs - the number of vehicle observations used to calculate all time
  Mean excess time ratio - the arithmetic mean of the ratio, by hour, of travel times to the best travel time
  Mean excess time ratio - weighted - the arithmetic mean of the ratio, by hour, of travel times to the best travel time, weighted by observations in that   hour - hour of the day (from 0 to 23)
  Mean excess iq ratio - the arithmetic mean of the ratio, by hour, of iq ranges to the best IQ range
  Mean excess iq ratio - weighted - the arithmetic mean of the ratio, by hour, of IQ ranges to the best IQ range, weighted by observations in that hour
  distance - the length of the route in metres

2. route_times.csv: Containing data for each hour, as graphed in the report, with the fields
  route_name - name of route
  hour - hour of the day (from 0 to 23)
  LQ_est - the travel time at the lowest quartile of speeds (that is the upper quartile of travel times) in seconds
  med_est - the travel time at the median travel speeds in seconds
  UQ_est - the travel time at the upper quartile of speeds (that is the lower quartile of travel times) in seconds
  LQ_est_char, med_est_char, UQ_est_char - the above but in human readable format
  n_obvs - the number of vehicle observations used to caculate the speeds for that hour

3. segment_summary.csv: containing summaries of the segments and their speeds used to calculate travel times
  route_name - the name of the route this data was generated for
  osm_id - an Open Street Map unqiue indentifier, valid at least at time of publication. A segment may appear in more than one route.
  hour - hour of day (from 0 to 23)
  n_obvs - the number of vehicle observations available for that hour and segment. This may be 0 in some cases in which case alternate methods were used to assume a distribution of speeds
  speed_limit - the speed limit. This report assumes all vehicles obey the speed limit. This was taken from OpenStreetMap where available and assumed based on road class and observed speed in others.
  UQ - the upper quartile of speed (kph)
  median - the median speed (kph)
  LQ - the lower quartile of speed (sph)
  distance - the distance traversed on this segment by the route - a segment may be used for different lengths on different routes

4. geometries.csv contains only whole route geometries. Individual segments can be obtained from OpenStreetMap.
