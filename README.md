# Sedimentary compositions in terms of weathering and provenance 

Data and `R` scripts utilised in the publication *"Major-element composition of sediments in terms of weathering and provenance: implications for crustal recycling"*.

## Code

The document `data_analysis.html` is an [R-markdown document](https://rmarkdown.rstudio.com/) containing code examples to recreate the analysis described in the data. This file can be viewed in any browser. 
The same document is also given in the raw `.Rmd` form, which can be opened in [R-studio](https://www.rstudio.com/).

This document demonstrates in `R` the application of principal component analysis on the dataset of sedimentary rock major element compositions, and the projection of other datasets onto these components. 

It also contains a function written in `R` which calculates the coefficients omega and psi for any major elemental composition (`find_coefficients`) as well as functions to calculate the model residuals (`find_residuals`) and the fitted values (`find_fit`). 

The scripts require `R` v3.6.1

## Data

Data used in the publication is contained in the folder `data/`. References for data sources is found in `data_references.pdf`, alongside the data. 
