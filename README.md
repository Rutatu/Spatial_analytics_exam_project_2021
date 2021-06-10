# Spatial_analytics_exam_project_2021

This repository if for the Spatial analytics exam paper. It contains data and data preprocessing and analysis script as R Markdown file. The project´s idea and goals are briefly described below. Analysis was done using CHC-hosted RStudioCloud server (Version 1.3.1073) as well as RStudio 1.4.1106 software installed locally.



# Happiness and green urban spaces: how green is happiness?
## Exploration of relationship between Green Urban Areas in European Union cities and Happiness Index

***Authors: Ruta Slivkaite (201805872@post.au.dk) and Bianka Szöllősi (201808610@post.au.dk)***


__Idea and goals__
This project investigates the role of the natural environment in happiness. In more detail, it investigate the link between the Happiness Index of European Union (EU) cities and the Green Urban Areas (GUAs) such as parks, forests and herbaceous vegetation associations in those cities. The presence and quantity or availability of GUAs may be more or less appropriate for analysing the role of GUAs in health enhancement and improvement of life´s quality (Poelman, 2016) , therefore we chose the quantitative statistical methods for our project. This project aims to capture the spatial aspect of the natural environment´s role in life satisfaction evaluation by looking at how the amount of GUAs, their proximity and the distribution of population around them is connected to the Happiness Index.  Our research paper asks the following general research questions: “How green is happiness?”, and  “Are cities with more individuals living closer to GUAs happier?”. The following hypotheses were formulated:

H1: The overall size of GUAs is higher in countries/cities with higher Happiness Index
H2: The happier the city/country the bigger the measure of GUA size per capita (calculated from total population count as well as population count within 400m distance from GUAs to capture the proximity element)
H3: The population is more densely distributed around GUAs (within 400m distance) in countries/cities with higher Happiness Index

__Statistical approach__
This project we will only explore the suitability and relevance of quantitative statistical methods, such as Pearson's correlation tests and spatial approach using  R studio software for testing our hypotheses. These digital tools will help us determine what kind of relationship there is between Happiness Index and the natural environment, which could potentially lead to further investigations and decision making advancing our well-being.

__Data__

Copernicus Urban Atlas 2018: 
https://land.copernicus.eu/local/urban-atlas/urban-atlas-2018?tab=metadata
https://land.copernicus.eu/user-corner/technical-library/urban_atlas_2012_2018_mapping_guide_v6-1.pdf

World Happiness Report 2020: 
https://worldhappiness.report/ed/2020/cities-and-happiness-a-global-ranking-and-analysis/
European GEOSTAT dataset 2018 (1km2 population grid, polygon data)
