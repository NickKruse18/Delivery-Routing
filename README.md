# Find the shortest delivery route

This package demonstrates the use of Linear Programming in solving shortest path problems. This package solves cases where some locations must be visited before others. Specifically, all locations come in pairs,
the location where a parcel is picked up and the location must be delivered. As such for every pair the pick up location must always be visited before its corresponding delivery location.
The computation time for the algorithm is incredibly sensitive to the amount of location pairs and it is recommended to stay at 5-6.


To install the package in R use: install.packages("directory/deliveryroute_1.0.0.tar.gz",  repos = NULL,  type = "source"), where 'directory' should be replaced with the file destination. Remember to replace any '\\' with '/'


To access the functions of the package it may be necessary to start every function call with deliveryroute::,  fx. to use the function SetupLeague type deliveryroute::SolvePath.


Every function has Rdocumentation so for more information about a function type fx. ?deliveryroute::Locations. 




Examples:


![Ex1](https://github.com/NickKruse18/Delivery-Routing/assets/97922500/234d094c-a0ad-4708-b6d7-4c50ff0189c0)

Here the map is of size 20 with 6 pairs of locations. Each pair is marked with a number from 1 to 6. The blue numbers are pick up locations and the reds are delivery locations. The black point is the starting location, and the red edge is where the route starts.


![Ex2](https://github.com/NickKruse18/Delivery-Routing/assets/97922500/cf59a92e-d19b-40a3-9835-326ea6e3f338)


![Ex3](https://github.com/NickKruse18/Delivery-Routing/assets/97922500/045f7d61-28b5-449f-b2ed-bdab69a2c188)
