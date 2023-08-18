# ImmaculateGridSPARQLQueries
This document provides DBpedia SPARQL queries that aid in filling in boxes for Baseball Reference's Immaculate Grid

Each query can be pasted into dbpedia's SPARQL endpoint found here https://dbpedia.org/sparql.

Limitations:
1. Occasionally, the query does not differentiate between teams played for and teams coached. For example, Ricky Bones will be a result for someone that played for the Mets and Nationals. However, Ricky Bones was a coach for both of these teams. This is a short of the way dbpedia scrapes wikipedia for their data. Here is the information box that the query pulls from. 
"As player *San Diego Padres *Milwaukee Brewers *New York Yankees *Cincinnati Reds *Kansas City Royals *Baltimore Orioles *Florida Marlins As coach *New York Mets *Washington Nationals (en)"
There is no real way to write the query to differentiate between "as player" and "as coach" in this text box.

2. 
