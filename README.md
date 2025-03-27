# VRPD-Dataset-for-delivery-and-surveillance

This data set is generated to evaluate the truck-and-drone collaborative system for delivery and surveillance tasks in disaster responses.


---------------------
DATA & FILE OVERVIEW
---------------------

Directory of Files:
  Revised Solomon instance:  
	c101.txt
	r101.txt
	rc101.txt
      Short description: The three txt files are obtained by revising the Solomon dataset.


        
  HK instance : 
	dD.npy
	dT.npy
	Nodes inf.xlsx
      Short description: This folder is the instance based on the HK island. Nodets inf.xlsx is about the node information, and dD.npy and dT.npy are the travel distances between two nodes for trucks and drones.


-----------------------------------------
DATA DESCRIPTION FOR: c101.txt, r101.txt and rc101.txt
-----------------------------------------
Variable List

    A. Name: CUST NO.
       Description: Index of the customer node

    B. Name: XCOORD.  YCOORD.
       Description: x and y location of the node

    C. Name: DEMAND
       Description: delivery demand (weight) of each node

    D. Name: SURVEILLANCE TIME
       Description: surveillance demand (time) of each node

    E. Name: Delivery_priority
       Description: Priority coefficient of the delivery task at the node

    F. Name: Surveillance_priority
       Description: Priority coefficient of the surveillance task at the node

    G. Name: Truck-reachable Node
        Yes = The node is truck-reachable
	No = The node is truck-unreachable

-----------------------------------------
DATA DESCRIPTION FOR: Nodes inf.xlsx
-----------------------------------------
Variable List

    A. Name: CUST NO.
       Description: Index of the customer node

    B. Name: Name
       Description: Name of the node

    C. Name: Latitude, Longitude
       Description: location information of the node

    D. Name: DEMAND
       Description: delivery demand (weight) of each node

    E. Name: SURVEILLANCE TIME
       Description: surveillance demand (time) of each node

    F. Name: Delivery_priority
       Description: Priority coefficient of the delivery task at the node

    G. Name: Surveillance_priority
       Description: Priority coefficient of the surveillance task at the node

    H. Name: Truck-reachable Node
        Yes = The node is truck-reachable
	      No = The node is truck-unreachable
