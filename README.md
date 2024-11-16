# Oil spills in New York State
*This is an example repository for UCSB's MEDS program EDS 220 class.*

## About
This repositroy contains a notebook `NY-state-spills-per-county.ipynb` analyzing data about spilling incidents of petroleum and other hazardous materials in the state of New York, USA.

After examining geospatial and tabular datasets, we create a choropleth map showing the number of oil spills per county in the state of New York from January to October 2023.
This map is located in the `images/` directory.

<figure>
<p align="center">
<img 
  src="/images/oil-spill.jpg" 
  width="800"
  >
  <figcaption>Workers from the Miller Environmental Group (MEG) dispose of oil particles from a 500 gallon oil spill near Jones Beach, N.Y., Friday, Nov. 23, 2007. 
  </figcaption>
</p>
</figure>

## Highlights

- Data wrangling and exploration with `pandas`
- Geospatial data wrangling with `geopandas`
- Merging of tabular and vector data
- Creating and customizing a choropleth map

## Data
New York State Department of Environmental Conservation (2023), *Spill Incidents* [Data file] Available from: https://data.ny.gov/Energy-Environment/Spill-Incidents/u44d-k5fk. Access date: November 3, 2023.

## Repository organization

```
eds220-oil-spills-sample-repo
│
├── README.md                     
├── NY-state-spills-per-county.ipynb  # Jupyter notebook for analysis
├── LICENSE                       
├── .gitignore                    
│
├── images/                       
│   ├── ny_state_spills_per_county.png  # Final choropleth map
│   ├── oil-spill.jpg             # Image used in the README
```



