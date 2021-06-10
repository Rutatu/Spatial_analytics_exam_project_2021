# Spatial_analytics_exam_project_2021

This repository is for the Spatial analytics exam paper. It contains data and data preprocessing and analysis script as R Markdown file. The project´s idea and goals are briefly described below. Analysis was done using CHC-hosted RStudioCloud server (Version 1.3.1073) as well as RStudio 1.4.1106 software installed locally.



# Happiness and green urban spaces: how green is happiness? Exploration of relationship between Green Urban Areas in European Union cities and Happiness Index

***Authors: Ruta Slivkaite (201805872@post.au.dk) and Bianka Szöllősi (201808610@post.au.dk)***


## Idea and goals
This project investigates the role of the natural environment in happiness. In more detail, it investigate the link between the Happiness Index of European Union (EU) cities and the Green Urban Areas (GUAs) such as parks, forests and herbaceous vegetation associations in those cities. The presence and quantity or availability of GUAs may be more or less appropriate for analysing the role of GUAs in health enhancement and improvement of life´s quality (Poelman, 2016) , therefore we chose the quantitative statistical methods for our project. This project aims to capture the spatial aspect of the natural environment´s role in life satisfaction evaluation by looking at how the amount of GUAs, their proximity and the distribution of population around them is connected to the Happiness Index.  Our research paper asks the following general research questions: “How green is happiness?”, and  “Are cities with more individuals living closer to GUAs happier?”. The following hypotheses were formulated:

H1: The overall size of GUAs is higher in countries/cities with higher Happiness Index
H2: The happier the city/country the bigger the measure of GUA size per capita (calculated from total population count as well as population count within 400m distance from GUAs to capture the proximity element)
H3: The population is more densely distributed around GUAs (within 400m distance) in countries/cities with higher Happiness Index

## Statistical approach
This project we will only explore the suitability and relevance of quantitative statistical methods, such as Pearson's correlation tests and spatial approach using  R studio software for testing our hypotheses. These digital tools will help us determine what kind of relationship there is between Happiness Index and the natural environment, which could potentially lead to further investigations and decision making advancing our well-being.

## Data

The datasets used for this project were included in this repository, except for the European GEOSTAT dataset 2018, which exceeded the size limit. The data can be downloaded using the links below.

Copernicus Urban Atlas 2018: 
https://land.copernicus.eu/local/urban-atlas/urban-atlas-2018?tab=metadata
https://land.copernicus.eu/user-corner/technical-library/urban_atlas_2012_2018_mapping_guide_v6-1.pdf

World Happiness Report 2020: 
https://worldhappiness.report/ed/2020/cities-and-happiness-a-global-ranking-and-analysis/

European GEOSTAT dataset 2018 (1km2 population grid, polygon data):
https://ec-europa-eu.ez.statsbiblioteket.dk:12048/eurostat/web/gisco/geodata/reference-data/population-distribution-demography/geostat


## Results

In conclusion, the aim of the present project was to serve as a stepping stone in investigating whether GUAs have an effect on the evaluation of personal happiness in individuals, with more empirical data. Relying on previous research, which emphasises the benefits of urban green space on mental health, we hypothesized that the overall size of GUAs is higher in countries/cities with higher happiness index (H1), the happier the city/country, the bigger the measure of GUA size per capita (H2) and that the population is more densely distributed around GUAs (within 400m distance) in countries/cities with higher happiness index. The results of Pearson's correlation analyses, however, were unable to support H1 and H2. H3, on the other hand, was confirmed by the results.

All in all, however, it cannot be concluded from the present study with certainty that there is a causational relationship between green spaces and personal well-being. It might be due to some of the limitations this project was facing, including low R values, only mildly generalizable data and simple statistical methods. Still, after applying some methodological improvements, the present study could benefit from being replicated, to further investigate the effects of GUAs on happiness. Future replications might show essential evidence that could later be implemented in order to rethink how we design cities we live in and how we engage with our surroundings - as a fairly simple thing like more greenery in front of our eyes could lead to the benefit of the whole population's mental health.

