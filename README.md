# README

Welcome to this Git repository where I am showcasing some of the plots made for the Regional Drought Early Warning Systems (RDEWS) project:

![onset error](https://github.com/whiteellie/model-error-rdews/blob/main/out/onset_error.png)
![recovery error](https://github.com/whiteellie/model-error-rdews/blob/main/out/onset_error.png)
![fscore](https://github.com/whiteellie/model-error-rdews/blob/main/out/onset_error.png)

Development is happening here: https://code.usgs.gov/water/RegionalDroughtEarlyWarning/modeling/model-eval/
Link is only accessible by USGS employees. 

## Audience
Primary audience is the model development team to use for iterative model development and secondary audience is hydrologists and watershed modelers in the scientific community. 

## Data Sources 
* Neural network models developed in the RDEWs project

## Process 
1) Made a pipeline that post-processes model results and produces tables with gages along the rows (~400 of them) and their associcated regression and classification errors along the columns.
2) The last phase of the pipeline produces the maps and its projections along latituted and longitude with `ggplot`.
3) Explanatory pane is developed and overlayed in Powerpoint and final image is saved as `*.png`. 

## Design Considerations
* Divergent and color palette was chosen to highlight the extremes of the variable-where the model performs very poorly and very well. The color palette is also colorblind-friendly (508 compliant).
* The rug on the horizontal and vertical axies of the scatterplots were added to show that the points in those plots are projections of the same points on the map. 
* The map and scatterplots were aligned and similarly sized to highlight their relatedness. 
* Map elements (i.e., state lines, north arrow, and scale) were added to geographically orient the user. 
* Explanatory panel was added to provide a quick reference to what the variable plotted is or how it is derrived. 

## Date Last Modified
05/24/2023

