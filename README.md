Transit Optimisation under Ride Hailing Competition and Traffic Congestion ( by Naman Goel)



Approach 1:

Introduction

In the subject of transportation planning, the Transit Network Design Problem (TNDP) has been extensively studied. It is a nonlinear optimization problem that deals with the construction of optimum public transportation networks and systems. Within the framework of a transportation network, attempts are made to balance the tradeoffs between utility maximization and cost reduction given specific resource limits.

Mainly the two types of problems are faced:
Increased ride hailing competition which is a direct result of improper transit network of public transportation which has led to the decrease in its ridership.
Increased cost of transportation operations as the decrease in ridership of public transit has resulted in less revenue whereas the operation cost lies the same.
 
Solution:
The argument is that the present transit network is inconvenient and ineffective for a huge section of the population. The objective is to reduce travel time and increase network coverage. The optimal location of transit stops is the first difficulty to tackle.
A new set of transit stops are initialized using block-level population data from the 2010 census by assigning weights to each intersection according to the population in its surrounding blocks. A suitable metric is defined to assign weights to each intersection by summing up the population of their surrounding blocks. After assigning weights to all the intersections, the transit stop locations are determined by finding out their reach within a suitable buffer zone.
 
After finding out the optimal locations of the stops ( proposed ), we find the location of the current stops using the shape files of the city. The population served by the current and proposed stops are then compared. 
After that the shortest path between two stops is calculated to reduce the travel time and operation costs.


Approach 2:

Introduction

The unstructured method to manage road traffic, which is mostly made up of everyday commuters, is an issue that any expanding city and metropolitan encounters. One of the issue factors is the clustering of cabs at specific places that travel specific routes, causing these geographic areas to become overcrowded. As a result, the traffic speed on main roads linking these hotspots of passenger pickup and drop-off slows.



Solution:

The first step in the process is to identify the hotspots that trigger cab clustering. After we've investigated these hotspots in a demographic region, we'll have a good sense of where major traffic originates and ends within a specific time window. Now here's the crux of our issue: these hotspots have more cabs than any other area, and at the same time, there's a drop point that will have more taxis than any other location. When we have a dataset that contains data for pair-wise pickup and drop sites, the picture becomes clearer.

