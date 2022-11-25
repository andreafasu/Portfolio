# Portfolio
Data Analysis 

## Introduction
An important activity for X is to buy and sell power on the European markets. Having an
informed view on the future production of power therefore allows for a competitive advantage when
placing bids and offers. 
One of the inputs to this view comes from production forecast for X's 
windfarms provided by a number of vendors. These vendors take into account the location of the 
windfarms, the placement of the wind turbines, the weather, and other factors and then provide 
daily forecast for the production for the windfarms for the next 24-hour period.

## Data
This repository contains two pickle files, `features.pkl` and `target.pkl`. 

`features.pkl` is a time-indexed Pandas dataframe with three columns, `0`, `1`, and `2`. The values 
represent the forecasted production from three forecast vendors for a portfolio of Ørsted windfarms 
(data has been transformed from its original). The units are MWh for the 30-minute window given by 
the index.
`target.pkl` contains the actual production from the portfolio for the same time range.
