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


## Date Last Modified
05/24/2023