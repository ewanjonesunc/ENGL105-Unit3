# U.S. Geological Survey Earthquake Repo

This is a repository containing instructional materials and a dataset for a project in ENGL105 at the University of North Carolina, Chapel Hill. 

The repository contains 1 [python notebook](https://github.com/ewanjonesunc/ENGL105-Unit3/blob/45a46b7f3f1181c0eaa7e9aec3a5ba41a27f8321/Creating%20a%20subset.ipynb), covering how to create a subset of data from a raw `.csv` file using Python3. 

It also contains two `.csv` files, found in the [Data](/Data) folder:
1. The file entitled [`EarthquakeData.csv`](https://github.com/ewanjonesunc/ENGL105-Unit3/blob/e42a94aafb6dd0110cc49eb71c0da05d1eadb940/Data/EarthquakeData.csv) contains global data from Nov. 6 2021 to Nov. 6 2022 on all earthquakes of magnitudes 3.5 to 10. It was sourced from the [U.S. Geological Survey's Earthquake Catalog](https://earthquake.usgs.gov/earthquakes/search/). 
2. The file entitled [`Earthquake_subset`](https://github.com/ewanjonesunc/ENGL105-Unit3/blob/e42a94aafb6dd0110cc49eb71c0da05d1eadb940/Data/Earthquake_subset.csv) was created using the same instructions found in the python notebook. It contains only data from the southern hemisphere, and is simplified to only include particular columns that are most relevant, like time, magnitude, depth, and latitude and longitude. It also includes a readable place indicator.

The subset extracted from the raw data might serve to answer research questions about the magnitude and depth of earthquakes in the southern hemisphere over time, or just by region over a full year.
