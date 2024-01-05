# COVID19_Forecasting
Forecasting evolution of COVID pandemic in the region of Catalonia. 

## Introduction
This repository contains a small project trying to predict the evolution of the COVID pandemic in Catalonia in 1, 3, and 5 weeks' time. The data used comes from an open-source database of the Government of Catalonia, keeping track of the cases, hospitalizations, and deaths due to COVID-19 and other conditions (https://sivic.salut.gencat.cat/dades_obertes). Some other information has been added about the presence of government restrictions, use of face masks or average monthly temperature, to add features and study their effect on the forecasting models. 

## Files in the Repository
**Preprocessing-FirstModels.ipynb:** Contains the first analysis and preprocessing of the data. Contains as well some first predictive models using feedforward neural networks.

**Models-Case-Hospitalizations-Deaths.ipynb:** Contains the predictive models at 1, 3, and 5 weeks for the cases of hospitalizations and deaths. The first models only consider the previous weeks' COVID cases, while others integrate as well information about government restrictions, masks, and mean temperature of the month. 

