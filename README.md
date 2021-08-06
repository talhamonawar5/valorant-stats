# Valorant ranked data analysis

A personal project that aims to analyze ranked data of the tactical-FPS Valorant through the pandas library and scikit-learn

## Description
The purpose of this project is to depict the disparites between each rank within the ranked system of the tactical-FPS shooter
Valorant. Through conducting an exploratory data analysis (EDA) by utilizing the Python pandas library,
we are able to show the more nuanced aspects of skill that differentiate players between each rank. 

The data was extrapolated from the website blitz.gg and processed into a .CSV file
Blitz.gg gets their data from API of the company that developed Valorant (Riot Games)

The project also consists of two machine learning models developed
using scikit-learn that predict the KD ratio and Average Combat score of a player based 
off of various statistics such as rank, win %, first blood %, etc.

For additional background information, the ranks are as follows in ascending order (lowest-highest rank)

Iron
Bronze
Silver
Gold
Platinum
Diamond
Immortal 
Radiant

There are three divisions from the Iron-Diamond ranks; however, for this project we will only use
the first division for each rank.

First blood % means the percentage of a player getting the first kill on an opponent within the round

The Vandal and Phantom are the two primary weapons within the game

## Caveats 

Datasets only consists of the ranked data from the last Act. The Valorant timeframe consists of Episodes and Acts. Each Episode contains three acts and each act lasts
approximately two months. Since the dataframe consists of data from one act only, the sample size is limited compared to what it could be if there were multiple acts.
I intend on importing data from multiple acts in order to advance the project.

Project was limited due to only having access to the data on blitz.gg. Since Riot Games Valorant API for ranked matches requires a Production API key I was limited
to only the data provided by blitz.gg.


## Authors
Talha Monawar

tam6131@psu.edu

## Acknowledgements
Datasets were extraploted from blitz.gg which uses Riot Games API in order to obtain their data

