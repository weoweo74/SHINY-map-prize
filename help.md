###  Purpose

**This Presidential Malaria Initiative:PMI-visualization** is a **Shiny** web application that allows users to generate summary statistics and visualise surfaces from the **Malaria Atlas Dataset** The application generates sub-national-level summary statistics for a range of malaria indicators. The aggregated sub-national-level statistics enable the interpretation of disaggregated, high-spatial resolution trends (5 km x 5 km), at the administrative level.

The application allows user interaction and creates interactive visualizations such as maps displaying mean values for each district selected by the user, and interactive tables ranking values. Users may select one country to analyse, all available districts within that country and up to four rasters for summary statistics generation and surface visualisation.

###  Structure

The 'Application' page is comprised of four main sections:

- Side panel. The side panel (left) details where the user may select input parameters, such as the country of interest, selected districts within that country and up to four surfaces to compare as produced by MAP.
- 'Map'. This tab visualises surfaces as provided by MAP, within an interactive plot which details sub-national names and boundaries as provided by the [FAO](http://www.fao.org/home/en/).
- 'Table'. This tab contains an interactive table ranking selected sub-national level based off of select indicator variables, as selected on the side panel.
- 'Output Report'. This tab contains a rendered report detailing summary statistics and plots as informed by user-selected input parameters. This tab is initiated by a button press (see "Generate Report Button")

**Generate Report Button**

When the "Generate Report" button is clicked, the application retrives summary statistics and raster layer visualisations for the selected input and renders them in the third output tab on the right-hand side of the application ("Output Report").

**Download Report Button**
To download the report generated and displayed in the "Output Report" tab, users can press this button to select a folder within their computer in which to download the report

### Dependencies
Data visualization currently available
-----------------------------------------
Geo-located point data	
Malaria parasite rate (PR; for P. falciparum and P. vivax)	
Administrative boundary shapefiles	Available now	
Predicted malaria infection risk, prevalence, and associated illness
Predicted prevalence of malaria-relevant blood disorders
Predicted mosquito vector distribution and relative abundance	
Intervention Coverage (ITNs; IRS; ACT)	Available now
Global travel time to cities	Available now

**This PMI-visualization is a referenced version of**MaDD** developed using **R** and **Shiny**



### References

- Andras Sali (2017). shinycssloaders: Add CSS Loading Animations to 'shiny' Outputs. R package version 0.2.0. https://CRAN.R-project.org/package=shinycssloaders

- Dean Attali and Tristan Edwards (2018). shinyalert: Easily Create Pretty Popup Messages (Modals) in 'Shiny'. R package version 1.0. https://CRAN.R-project.org/package=shinyalert

- Eric Bailey (2015). shinyBS: Twitter Bootstrap Components for Shiny. R package version 0.61. https://CRAN.R-project.org/package=shinyBS

- Erich Neuwirth (2014). RColorBrewer: ColorBrewer Palettes. R package version 1.1-2. https://CRAN.R-project.org/package=RColorBrewer

- H. Wickham. ggplot2: Elegant Graphics for Data Analysis. Springer-Verlag New York, 2016.

- Hadley Wickham (2018). stringr: Simple, Consistent Wrappers for Common String Operations. R package version 1.3.1. https://CRAN.R-project.org/package=stringr

- Pebesma, E.J., R.S. Bivand, 2005. Classes and methods for spatial data in R. R News 5 (2), https://cran.r-project.org/doc/Rnews/.

- Pfeffer, D.A., Lucas, T.C., May, D., Harris, J., Rozier, J., Twohig, K.A., Dalrymple, U., Guerra, C.A., Moyes, C.L., Thorn, M., Nguyen, M., et al. 2018. malariaAtlas: an R interface to global malariometric data hosted by the Malaria Atlas Project. Malaria Journal, 17(1), p.352.

- R Core Team (2018). R: A language and environment for statistical computing. R Foundation for Statistical Computing, Vienna, Austria. URL https://www.R-project.org/.

- R Core Team (2018). R: A language and environment for statistical computing. R Foundation for Statistical Computing, Vienna, Austria. URL https://www.R-project.org/.

- Robert J. Hijmans (2019). raster: Geographic Data Analysis and Modeling. R package version 2.8-19. https://CRAN.R-project.org/package=raster

- Winston Chang (2018). shinythemes: Themes for Shiny. R package version 1.1.2. https://CRAN.R-project.org/package=shinythemes

- Winston Chang and Barbara Borges Ribeiro (2018). shinydashboard: Create Dashboards with 'Shiny'. R package version 0.7.1. https://CRAN.R-project.org/package=shinydashboard

- Winston Chang, Joe Cheng, JJ Allaire, Yihui Xie and Jonathan McPherson (2018). shiny: Web Application Framework for R. R package version 1.2.0. https://CRAN.R-project.org/package=shiny
- MaDD. (2015). Malaria-ALTAL-MAP database and MaDD
