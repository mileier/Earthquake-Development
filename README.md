# Earthquake-Development
Earthquake Development over time

1. Installations

Anaconda or MiniConda, plus the following installs
	conda install -c conda-forge contextily 
	conda install -c main seaborn
	conda install -c main geopandas
	conda install -c main plotly

	
2. Project Motivation

The motivation for this project was to find an interesting question to elaborate on 
for a Udacity Data Scientist Nanodegree project.
I have been curious about the development of earthquake data over time for a while, 
so I decided to on to explore this.

Some other ideas i.e. CoVid / vaccination data were dismissed, since they already 
have really good visual representations readily available, i.e. on the WHO website.

The choosen data was the only official source with such long-lasting historic data
that I was able to find. Often, other data sets are only on one month or so, since
they don't include a pre-selection on "severe" earthquakes.


3. File Descriptions

* significant-hist-earthquakes.csv
Used Data Source
https://www.ngdc.noaa.gov/hazel/view/hazards/earthquake/search
Easier Access through 
https://www.qgistutorials.com/de/docs/importing_spreadsheets_csv.html => signif.txt

* earth-dev-sig.ipynb
Jupyter Notebook used to read in the earthquake data, 
get an overview of the available data set, and to create some graphs
to explore the question at hand, and also to create some visualizations 
for the associated medium.com article:
https://medium.com/@miriam.gobel/earthquakes-are-they-getting-worse-fe932f343bee

* PNG-Files
Visualizations, created using the Jupyter notebook.


4. How to Interact with your project

Feel free to explore more of the data yourself, by creating a fork and 
experimenting yourself with the existing Jupyter notebook and the earth quake data set.


5. Licensing, Authors, Acknowledgements, etc.

The https://medium.com/@miriam.gobel/earthquakes-are-they-getting-worse-fe932f343bee 
title picture is free for commercial use without a citation:
https://pixabay.com/de/photos/erdbeben-seismograph-seismische-3167693/

Thanks to Ujaval Gandhi for providing easier access to the dataset on 
https://www.qgistutorials.com/de/docs/importing_spreadsheets_csv.html => signif.txt