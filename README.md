Hello, and welcome to my project analyzing spatial variation in immigration enforcement! 

This repo is still a work in progress, and I have yet to automate my process (that is the next step!)

However, my analysis is still completely reproducible. If you would like to reproduce my results, follow these steps:
1. Download the following data:
  - ICE encounters from the Data Deportation Project: https://deportationdata.org/data/ice.html
  - Census data on nativity and citizenship: https://data.census.gov/table/ACSDT5Y2023.B05001?q=Citizenship&g=010XX00US$0500000_040XX00US15
  - Census data on race/ethnicity:  https://data.census.gov/table/DECENNIALDHC2020.P9?q=Race+and+Ethnicity
  - Data and Area of Responsibility (AOR) geopackage (with help from Emma Brice): 

2. Run the preprocessing files in the following notebooks:
  - preprocessing_encounters.ipynb
  - preprocessing_nat_cit.ipynb
  - preprocessing_race_ethn.ipynb

3. Conduct spatial clustering of ICE offices and merge county demographics data with encounters data.
  - merging_clustering.qmd

4. Performing modeling!
   - modeling.qmd

5. Prepare for mapping local coefficients.
   - mapping_prep.qmd
