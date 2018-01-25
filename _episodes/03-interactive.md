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


- Stream web camera from Finse railway station and show the last image taken from the Finse Research Centre
-  Regularly create a map with temperature values (in degrees Celcius) from Weather Stations available from Weather Underground in the "Finse" region (Finse region at large)
- Add temperature values from Finse Research Stations with a different color to clearly distinguish Weather Underground data from Finse Research Stations.
-  On the same map, allow users to select the variable to plot (temperature, wind direction, wind speed, relative humidity, pressure, etc.).
- Create a summary table for Weather underground stations and Finse Research Centre Stations
- Allow user to select a station (by clicking) and show on another plot historical data (timeserie) where the user can select the start and end date.
- Show information on the battery of all Finse Research Stations. This will allow Laura to monitor the status of each stations (when the battery is down, she cannot receive data).

# Stream web camera

Laura can get live images from [Finse railway station](http://www.bt.no/tv/embed/?id=100521) and there is also a webcam on the roof of [Finse Research Centre](http://www.finse.uio.no/news/webcam/) (updated every hour between 6am and 6pm). The main purpose of the camera is to make it possible for researchers to follow the snow melt-off in the spring.

Laura needs to:

- Display the last available image from [Finse Research Centre](http://www.finse.uio.no/news/webcam/)
- Livestream [Finse railway station](http://www.bt.no/tv/embed/?id=100521)

Since we are viewing our jupyter notebook in a web browser, we can also render HTML content directly in the notebook. In fact, you can return virtually anything:

- image
- audio
- video

~~~
from IPython.display import HTML

HTML('<iframe width="560"  height="315" src="http://www.finse.uio.no/news/webcam/dagens.jpg"></iframe>')
~~~
{: .python}

<figure>
 <a href="http://www.finse.uio.no/news/webcam/dagens.jpg">
	<img src="http://www.finse.uio.no/news/webcam/dagens.jpg"></a>
	<figcaption><i> Most recent picture (updated every hour between 6am and 6pm) from Finse Research Centre<br>
	Source: http://www.finse.uio.no/news/webcam</i>
	</figcaption>
</figure>


A string is passed within `HTML` and you need to use `HTML` (Hyper Text Markup Language) syntax.  HTML is the standard markup language for creating Web pages and an in-depth description of this language is out of scope now.

And here we use iframe HTML tag. An iframe is used to display a web page within a web page and this is what we
do here as we display the entire webpage [http://www.finse.uio.no/news/webcam/dagens.jpg](http://www.finse.uio.no/news/webcam/dagens.jpg).

We also added the size (width and height) of our webpage (size we want to have in our jupyter notebook).

For more information on how to include webpage in HTML using ifram tag, look [here](https://www.w3schools.com/html/html_iframe.asp).

## Stream web camera

We apply the very same recipe to display the livestream camera from Finse Railway station:

~~~
from IPython.display import HTML
HTML('<iframe width="560"  height="315" src="http://www.bt.no/tv/embed/?id=100521" allowfullscreen="true"></iframe>')
~~~
{: .python}

Here we display the entire webpage [http://www.bt.no/tv/embed/?id=100521](http://www.bt.no/tv/embed/?id=100521).



	<iframe width="560" height="315" src="http://www.bt.no/tv/embed/?id=100521" frameborder="0" allowfullscreen></iframe>
	<figure>
	<figcaption><i> Livestreaming from Finse Railway webcam<br>
	Source: http://www.bt.no/tv/embed/?id=100521</i>
	</figcaption>
</figure>


## Select camera with python interactive widget

## From jupyter notebook to jupyter dashboard


# Create an interactive map for plotting geospatial data

## Requirements

We need to install the following python packages:
- folium



> ## Install folium using Anaconda navigator
>
> - Remember how we installed jupyter_dashboards and jupyter_dashboards_bundlers python packages in our environment jupyter_dashboards and
> follow the same instructions to install folium
> Use a **green sticky note** to signal that you have successfully installed this package
> or the **red sticky note** if you encountered any problems.
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
