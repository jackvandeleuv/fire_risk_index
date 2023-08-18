## Set up guide

To replicate this project, perform the following steps.

#### Download data files

Download all Fire Hazmat datasets from years 2012-2021 inclusive from the [FEMA website](https://www.fema.gov/about/openfema/data-sets/fema-usfa-nfirs-annual-data), and place each one in the data folder in the project root. Make sure to extract all zipped folders, including zipped subfolders inside the original zipped folder. 

(Note: The NFIRS dataset will take up around 30 gigabytes, once processed by the load_nfirs notebook.)

Also place the following three csv files from the HUD GIS Helpdesk in the data folder. (This project used the data files published August 15th, 2023.)

* [Public_Housing_Buildings.csv](https://hudgis-hud.opendata.arcgis.com/datasets/HUD::public-housing-buildings-2/about)
* [Public_Housing_Developments.csv](https://hudgis-hud.opendata.arcgis.com/datasets/HUD::public-housing-developments-1/about)
* [Public_Housing_Authorities.csv](https://hudgis-hud.opendata.arcgis.com/datasets/HUD::public-housing-authorities-1/about)

#### Run data processing/cleaning notebooks

Once you have extracted the zipped FEMA datasets, run these four notebooks in the following order:

1) load_nfirs.ipynb
2) link_public_dev_pha.ipynb
3) clean_public.ipynb
4) match_clean_fire_data.ipynb

After running all four notebooks in order, you can run any of the other notebooks.
