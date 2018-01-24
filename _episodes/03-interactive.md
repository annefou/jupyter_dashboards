---
title: "Interactive research"
teaching: 0
exercises: 0
questions:
- "How to use jupyter dashboards for our research project?"
objectives:
- "Understand how to add interactivity with jupyter dashboards and widgets"
keypoints:
- "Take a concrete example and illustrate how to use jupyter dashboards and widgets"
---


# Storyline

Laura has just started her PhD program as part of the [Land-Atmosphere Interaction in Cold Environments](http://www.mn.uio.no/geo/english/research/groups/latice/) (LATICE) project at University of Oslo, Department of Geosciences, Norway. She is interested in exploring
field data from the [Finse Research Centre](http://finse.uio.no). [Finse Alpine Research Center](http://finse.uio.no) is located in the northwestern part of the Hardangervidda mountain plateau and is of great interest for scientists in particular biologists, geologists, geophysicists.


<script src="https://embed.github.com/view/geojson/annefou/jupyter_dashboards/gh-pages/data/Hardangervidda.geojson"></script>

In addition to field data from Finse Research Centre, Laura wishes to use data from other Weather Stations available from [Weather Underground](https://www.wunderground.com/). She would need to clearly identify in her plots the data sources (Weather Underground or Finse Research Stations).

A large variety of data is therefore available to her and Laura would like to create the following outputs to better understand her project and show what [Finse Research Centre](http://finse.uio.no) is about:

-  Regularly create a map with temperature values (in degrees Celcius) from Weather Stations available from Weather Underground in the "Finse" region (Finse region at large)
- Add temperature values from Finse Research Stations with a different color to clearly distinguish Weather Underground data from Finse Research Stations.
-  On the same map, allow users to select the variable to plot (temperature, wind direction, wind speed, relative humidity, pressure, etc.).
- Create a summary table for Weather underground stations and Finse Research Centre Stations
- Allow user to select a station (by clicking) and show on another plot historical data (timeserie) where the user can select the start and end date.
- Show information on the battery of all Finse Research Stations. This will allow Laura to monitor the status of each stations (when the battery is down, she cannot receive data).

# Create an interactive map for plotting geospatial data

## Requirements

We need to install the following python packages:
- folium


> ## Install folium using Anaconda navigator
>
> - Remember how we installed jupyter_dashboards and jupyter_dashboards_bundlers python packages in our environment jupyter_dashboards and
> follow the same instructions to install folium
>
> - Test your newly installed package
>
> > ## Solution
> > Open Anaconda Navigator, click on "Environments"
> > Make sure you select the right working environmment "jupyter_dashboards"
> > Select "Not installed" and search for folium and install it
> >
> > To check the installation go to an open jupyter notebook (jupyter_dashboards environment) or create a new one:
> > Type
> > `import folium`
> >
> > if your installation was successful, the previous command should return with no errors.
> {: .solution}
{: .challenge}


# Create an interactive table with Finse and Weather underground data

# Create interactive timeseries (2D-plot)

# Arrange your plots in your jupyter dashboard
