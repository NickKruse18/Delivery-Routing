# Find the shortest delivery route

This package demonstrates the use of Linear Programming in solving shortest path problems. This package solves cases where some locations must be visited before others. Specifically, all locations come in pairs,
the location where a parcel is collected and the location must be delivered. As such for every pair the collection location must always be visited before its corresponding delivery location.


To install the package in R use: install.packages("directory/deliveryroute_1.0.0.tar.gz",  repos = NULL,  type = "source"), where 'directory' should be replaced with the file destination. Remember to replace any '\\' with '/'


To access the functions of the package it may be necessary to start every function call with deliveryroute::,  fx. to use the function SetupLeague type deliveryroute::SolvePath.


Every function has Rdocumentation so for more information about a function type fx. ?deliveryroute::Locations. 


#Examples:


![Ex1](https://github.com/NickKruse18/Delivery-Routing/assets/97922500/234d094c-a0ad-4708-b6d7-4c50ff0189c0)
