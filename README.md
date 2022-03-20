# Factors-that-affect-happiness
This repo contains an R project file for my paper "Possible factors affecting Canadian Family’s feelings about life".

## Overview
In this paper, we conducted the research on the factors which may have an impact on people’s feelings about life based on the General Social Survey(GSS). After screening and comparison, we found that the factors that may affect people’s feelings about life in the survey include age, respondent income, sex, average working hours, education level and feelings about life.

The GSS data used in this paper comes from Statistics Canada: https://www150.statcan.gc.ca/n1/pub/89f0115x/89f0115x2013001-eng.htm#a6.
It can be also obtained from CHASS, the data centre of University of Toronto: http://dc.chass.utoronto.ca/myaccess.html.

## Files Structure
This repo contains three folders: inputs, outputs, and scripts. 

- Inputs folder contains the GSS data file, a dict.txt file and labels.txt file which provides information on the survey data 
- Outputs folder contains the paper, R Markdown file of the paper, and references
- Script folder contains the R file that reorganizes and cleans the GSS family survey dataset

## How to generate the paper
- Request original data from the place in the data folder
- Open paper3.Rproj in RStudio
- Install libraries using install.packages() if necessary
- Run gss_cleaning.R
- Run paper3.Rmd
