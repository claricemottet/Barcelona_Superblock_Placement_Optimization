# Superblock Placement Optimization in Barcelona

With the goal of creating a healthier city environment through the increase in public use space and reduction in air pollution while minimizing impact to commuters, we seek to identify an optimal location to incorporate a Superblock within the city of Barcelona. By determining the Nash equilibrium and social equilibrium of traffic flow on Barcelona as a result of incorporating one Superblock at a time, we analyze best placement options tied to overall travel time, travel cost and Price of Anarchy.

The file Barcelona_Superblocks.pdf details the motivation of analysis, the methodology used and results.

The road network data for BCN comes from https://github.com/bstabler/TransportationNetworks.

TransportationNetworks_CM.py is an altered file from https://nbviewer.org/github/PyTrans/Urban-Network-Analysis/blob/master/Trip_Assignment-Frank-Wolfe_Algorithm.ipynb where the class of functions that calculated the nash equilibrium and social equilibrium is updated to allow for superblock placement instead of single road closure.

networks_bcn.ipynb is the main program that calculates travel time, travel cost and Price of Anarchy related to individual superblock placements. 

networks_bcn_pictures.ipynb is for visualizing the overall road network of BCN, the optimal Superblocks and the worst Superblocks.
