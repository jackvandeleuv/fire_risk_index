## Presentation

This project was presented to staff at the U.S. Department of Housing and Urban Development on August 2023. Download or view that presentation [here.](https://github.com/jackvandeleuv/fire_risk_index/blob/main/8-16-23%20Presentation%20(v1.0).pdf)

## Set up guide

To replicate this project, download all Fire Hazmat datasets from years 2012-2021 inclusive from the [FEMA website](https://www.fema.gov/about/openfema/data-sets/fema-usfa-nfirs-annual-data), and place each one in the data folder in the project root. Make sure to extract all zipped folders, including zipped subfolders inside the original zipped folder. 

(Note: The NFIRS dataset will take up around 30 gigabytes, once processed by the load_nfirs notebook.)

Once you have extracted the zipped FEMA datasets, run these four notebooks in the following order:

1) load_nfirs.ipynb
2) link_public_dev_pha.ipynb
3) clean_public.ipynb
4) match_clean_fire_data.ipynb

After running all four notebooks in order, you can run any of the other notebooks.
