# Association Rules in DOTA 2 Hero Drafting

Project Objective
This short project seeks to use Apriori Item Basket Analysis to find perceived hero association rules in DOTA 2 Drafting

Methods Used
Apriori Item Basket Analysis
Data Visualization

Technologies
Python - Pandas Data Manipulation
Python - Seaborn Data Visualisation
R - Tidyverse data manipulation
R - Apriori using the Arulez package
Gephi - Graphical visualisation

Project Description
Merging files in the original database and futher data manipulation created a file of approximately 100,000 observations, with each observation being a unique team, containing the heroes chosen by each player in the team.
This file was imported into R in order to use the Arulez package for Apriori Item Basket Analysis.
Many assocation rules were found, and, using Gephi, hero associations could be visualised with reference to indicators such as support and lift. 
The results were that many known 2 and 3 hero synergies were confirmed by association rules, and many without a known explanation could be investigated. A statistician working on the game could seek to understand strong association rules in the context of the game, to better understand players, implement balance changes and so on.

Note on Code
Full code and files may be uploaded in future

References and Accreditation
All credit for the original 50k ranked ladder matches to Devin Anzelmo
Kaggle dataset can be found though the below link
https://www.kaggle.com/devinanzelmo/dota-2-matches
