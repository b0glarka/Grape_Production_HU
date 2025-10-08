# grape_production_hu
## DS 1 Mini Project - Annual Grape Production in Hungary

Date - October 08, 2025\
Student - Boga Petruska\
Class - ECBS5293: Data Science 1, Fall 2025

This is README describes my DS 1 mini project, which plots annual wine grape production in Hungary from 2013-2024 based on Eurostat data.

Code can be found in the code/ folder in the form of a notebook entitled "grape_prod_plot_mpl.ipynb". Final output  (plot and CSV) is saved in output/.

## Data

Eurostat - Grapes by Production- https://ec.europa.eu/eurostat/databrowser/product/page/TAG00121
Downloaded file "estat_tag00121.tsv.gz" and stored in data/raw/.
Extracted TSV file "estat_tag00121.tsv" and moved to data/processed/.

Eurostat - Downloaded CROPS codes list from https://ec.europa.eu/eurostat/databrowser/bulk?lang=en&selectedTab=codeList to identify grapes used in wine production. 
Downloaded file "ESTAT_CROPS_12.0.tsv.gz".
Extracted TSV file "ESTAT_CROPS_12.0.tsv" - reviewed codes and determined that 
"W1100	Grapes for wines" is code needed to filter data in "estat_tag00121.tsv" for data that pertains to wine grapes. As a reference stored "ESTAT_CROPS_12.0.tsv" in docs/.

## Folder Structure
```
grape_production_hu/
├── code/
│ └── grape_prod_plot_mpl.ipynb
├── data/
│ ├── processed/
│ │ └── estat_tag00121.tsv
│ └── raw/
├── docs/
│ └── DS 1 - Mini Project - Assignment, 2025.10.04.pdf
├── output/
│ ├── HU_grape_plot.png
│ └── HU_grape_prod.csv
├── .gitignore
├── environment.yml
├── LICENSE
├── README.md
├── requirements.txt
```
## Requirements

### Environment:

How to get the development/analysis env running - 

##### Option 1 (conda)
```
conda env create -f environment.yml
conda activate grape_hu_env
```

##### Option 2 (pip)

```
pip install -r requirements.txt
```

#### Main Dependencies
- **Python** 3.12 or higher
- **jupyter / ipykernel** – running notebooks
- **pandas** – data manipulation and analysis
- **matplotlib** – plotting and visualization
- **warnings**

### Configuration:

Transformed data and plot is saved in output/
- HU_grape_prod.csv - values shown on plot in CSV
- HU_grape_prod.png - plot 

### Instructions: 

After setting up environment or installing via *pip*, navigate to the code/ folder and execute grape_prod_plot_mpl.ipynb.

Run all cells of code.
Output will be placed in output/ (plot and CSV of data).

## Contact Info
Boga Petruska\
Petruska_Boga@student.ceu.edu
