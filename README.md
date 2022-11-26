# U.S. Geological Survey Earthquake Repo

This is a repository containing instructional materials and a public dataset, intended for future scientific analysis by seismologists. Created for the public science organization Interstice Science. 

## Contents and source

The repository contains 1 [python notebook](https://github.com/ewanjonesunc/ENGL105-Unit3/blob/45a46b7f3f1181c0eaa7e9aec3a5ba41a27f8321/Creating%20a%20subset.ipynb), covering how to create a subset of earthquake data from a raw `.csv` file using Python3. 

It also contains two `.csv` files, found in the [Data](/Data) folder:
1. [`EarthquakeData.csv`](https://github.com/ewanjonesunc/ENGL105-Unit3/blob/e42a94aafb6dd0110cc49eb71c0da05d1eadb940/Data/EarthquakeData.csv) contains global data from Nov. 6 2021 to Nov. 6 2022 on all earthquakes of magnitudes 3.5 to 10. It was sourced from the [U.S. Geological Survey's Earthquake Catalog](https://earthquake.usgs.gov/earthquakes/search/).
2. [`Earthquake_subset`](https://github.com/ewanjonesunc/ENGL105-Unit3/blob/e42a94aafb6dd0110cc49eb71c0da05d1eadb940/Data/Earthquake_subset.csv) was created using the same instructions found in the python notebook. It contains only data from the southern hemisphere, and is simplified to only include particular columns that are most relevant, like time, magnitude, depth, and latitude and longitude. It also includes a readable place indicator.

## Purpose

Interstice Science has a strong interest in seismological research, especially research questions related to magnitude and depth of earthquakes in the southern hemisphere, where it is based. Any analysis of change in these variables over time, or of the full region over a year, is of great interest to I.S. 

## Visualization

Part of the subset, distribution of earthquakes in the southern hemisphere by magnitude, can be visualized like so: 

![Earthquakes in the Southern Hemisphere by Magnitude](/Data/SouthernEarthquakesVisualization.png)

The especially dark red-purple circles create lines, illustrating what is sometimes informally called the "ring of fire" or the dividing lines of Earth's tectonic plates. They roughly line up with the following map, as the most intense earthquakes most commonly happen at these junctures.

![Tectonic Plates Map](/Data/TectonicPlatesMap.png)
