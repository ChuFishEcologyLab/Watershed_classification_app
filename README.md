# Watershed_classification_application
## About this Application
This app classifies watersheds in Canada for four conservation objectives (area-based protection, habitat restoration, at-risk species management, and non-native species management) based on the methods outlined in Chu et al. (submitted)

### Watershed scale
National watershed classifications are available through this app. These are based on level 6 HydroBASIN watersheds (Lehner and Grill, 2013).

### Weighting scheme
Default values to weight each watershed index are based on expert scores but users can customize the weightings by sliding the cursors left or right.

**Six watershed indices are considered for each conservation objective:**

**Watershed stress**
Intensity of human activities in a watershed based on cumulative threat dataset (Hirsh-Pearson et al., 2022). Scaled to range from 0 to 100.

**Fish species at risk richness**
Number of COSEWIC listed fish species at risk with a watershed. Scaled to range from 0 to 100.

**Fish species richness**
Number of fish species (including native, foreign, and translocated species) within a watershed. Scaled to range from 0 to 100.

**Community rarity**
Index of the relative rarity of fish species within in the amount, from Minns (1987). Scaled to range from 0 to 100.

**Community change**
Index of the amount of change in a fish community between the native species pool and the species found in each watershed. Scaled to range from 0 to 100.

**Climate change**
Index of the forward bioclimatic velocitiy in a watershed by 2055 under the RCP 4.5 scenario (Adaptwest Project, 2023; Carroll, 2023). Scaled to range from 0 to 100.

### Watersheds ranked within ecoregions?
Select whether you want watersheds to be ranked within their freshwater ecoregion (i.e. high rankings = high for that ecoregion). Default (unchecked) value is that rankings are conducted at a national scale.

### References
AdaptWest Project. (2023). Gridded CMIP6-based climatic velocity data for North America at 1km resolution. Available at adaptwest.databasin.org (accessed August 2024).
Carroll, C. (2023). Velocity of climate change for North America based on CMIP6 GCMs [Data set]. Zenodo. doi.org/10.5281/zenodo.10631707.
Chu et al. submitted. Classification of Canadian watersheds for freshwater fishes and fish habitat conservation 
Hirsh-Pearson, K., Johnson, C. J., Schuster, R., Wheate, R. D., & Venter, O. (2022). Canada’s human footprint reveals large intact areas juxtaposed against areas under immense 
anthropogenic pressure. FACETS, 7(1), 398-419. 
Lehner, B., Grill G. (2013). Global river hydrography and network routing: baseline data and new approaches to study the world’s large river systems. Hydrological Processes, 27(15): 2171–2186.
Minns, C. K. (1987). A method of ranking species and sites for conservation using presence-absence data and its application to native freshwater fish in New Zealand. New Zealand Journal of Zoology, 14(1), 43–49. 

### Packages
R Studio 2024.12.1 Build 563 Posit team (2025). RStudio: Integrated Development Environment for R. Posit Software, PBC, Boston, MA.;
bslib 0.9.0 Sievert C, Cheng J, Aden-Buie G (2025). bslib: Custom 'Bootstrap' 'Sass' Themes for 'shiny' and 'rmarkdown'. R package version 0.9.0.9000;
shiny 1.11.1 Chang W, Cheng J, Allaire J, Sievert C, Schloerke B, Aden-Buie G, Xie Y, Allen J, McPherson J, Dipert A, Borges B (2025). shiny: Web Application Framework for R. R package version 1.12.0;
shinybusy 0.3.3 Meyer F, Perrier V (2024). shinybusy: Busy Indicators and Notifications for 'Shiny' Applications. R package version 0.3.3; 
shinyjs 2.1.0 Attali D (2022). shinyjs: Easily Improve the User Experience of Your Shiny Apps in Seconds. R package version 2.1.0; and, 
leaflet 2.2.3 Cheng J, Schloerke B, Karambelkar B, Xie Y, Aden-Buie G (2025). leaflet: Create Interactive Web Maps with the JavaScript 'Leaflet' Library. R package version 2.2.3.9000.
