# leaflet-challenge

## Background
#The United States Geological Survey, or USGS for short, is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment, and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes.

The USGS is interested in building a new set of tools that will allow them to visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. In this challenge, you have been tasked with developing a way to visualize USGS data that will allow them to better educate the public and other government organizations (and hopefully secure more funding) on issues facing our planet.

## Instructions
#The instructions for this activity are broken into two parts:

# Part 1: Create the Earthquake Visualization
1. Get your dataset. To do so, follow these steps:

The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the USGS GeoJSON Feed page and choose a dataset to visualize.
2. Import and visualize the data by doing the following:

Using Leaflet, create a map that plots all the earthquakes from your dataset based on their longitude and latitude.
Your data markers should reflect the magnitude of the earthquake by their size and the depth of the earthquake by color. Earthquakes with higher magnitudes should appear larger, and earthquakes with greater depth should appear darker in color.
Hint: The depth of the earth can be found as the third coordinate for each earthquake.
Include popups that provide additional information about the earthquake when its associated marker is clicked.
Create a legend that will provide context for your map data.

# Part 2: Gather and Plot More Data (Optional with no extra points earning)
Perform the following tasks:

Plot a second dataset on your map to illustrate the relationship between tectonic plates and seismic activity. You will need to pull in this dataset and visualize it alongside your original data. Data on tectonic plates can be found at Tectonic Plates Dataset.
This part is completely optional; you can complete this part as a way to challenge yourself and boost your new skills.
Perform additional tasks like adding other base maps to choose from and putting each dataset into separate overlays that can be turned on and off independently.
Add layer controls to your map.
