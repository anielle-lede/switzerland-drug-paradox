
# Switzerland's Drug Paradox

My very first data journalism story exploring the gap between cocaine consumption 
indicators and police-recorded drug offences in Switzerland. 

## Story

In terms of cocaine residues in wastewater, Switzerland ranks 8th out of 41 European countries—and has been among the top countries since 2014. Yet police-recorded drug offences have fallen by nearly 50% since 2009. Also interesting: the profile of suspected offenders has shifted significantly toward older age groups.

This piece examines what two very different datasets reveal about 
Switzerland's drug landscape, and shows how they diverge.

## Data sources

- **European Union Drugs Agency** — Wastewater Analysis and Drugs in 
  Europe (SCORE network), latest available year  
  https://www.emcdda.europa.eu/topics/wastewater-analysis

- **Swiss Federal Statistical Office (BFS)** — Police Crime Statistics 
  (PKS) 2009–2025  
  https://www.bfs.admin.ch/news/de/2026-0089

## What's in this repo
switzerland-drug-paradox/

docs/index.html # Main story page
  map-step-1.svg # Switzerland base map (scrollytelling step 1)
  map-step-2.svg # Partial city data (scrollytelling step 2)
  map-step-3.svg # Full city data (scrollytelling step 3)

Analyse_1_drugproject.ipynb # Cleaning and analysis of EUDA wastewater data

Analyse_2_drugproject.ipynb # Cleaning and analysis of BFS police statistics

data/
  cocaine_country_ranking.csv
  drug_offences_by_age.csv
  swiss_cocaine_cities.csv
  swiss_cocaine_map.csv
  swiss_drug_offences_2009_2025_clean.csv
  swiss_drugs_heatmap.csv
  switzerland_drug_offences_trend.csv
  switzerland_drug_ranking_datawrapper.csv

Charts are embedded via [Datawrapper](https://www.datawrapper.de/).  
Maps were created also in Adobe Illustrator from EUDA wastewater data.

## How to view locally

Just open `index.html` in a browser.

## Author

Anielle Peterhans — Lede Program, Columbia Journalism School, 2026
