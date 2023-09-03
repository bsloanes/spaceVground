# spaceVground
Coding completed in 2018 and 2020. Uploaded in 2023. Internal research pending. 
Uses Pyphot package to calcualte stellar spectra and colors. 
Goal of this research was to determine the disparity in spectra and color calculations between space-based and ground-based telescopy. 
0. Method to locate files internally, write and sort based on star name and classification (in earlier in version to be uploaded). 
Using open-source stellar flux density and error data:
1. Generate 1000 synthetic flux density calculations for each star analyzed with each a ground and two space-based telescopes. ~40 stars x 3 telescopes x 1000 synthetic files = 120,000 files.
2. Calculate spectra and colors using PyPhot.
3. Plot space-based against ground-based analysis.
4. graphsInterim demonstrates two major facets of the space vs ground-based telescope discrepancy: 
I. The color-color divide (stratification of differently-shaped data points) between different stellar types
II. The correlation is not 1:1 between different telescopes' calculations, as per the slope value. 
* researchCopy attempts to fix endStream errors in graphsInterim. Research pending and code is to be revisited. To appear in American Astronomical Society in 2023. 
