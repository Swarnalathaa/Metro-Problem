# Metro-Problem

I have implemented Metro/subway network as graph. Stations are represented by the graph's node/vertices and all connecting path between the station represnt the edges.

We are provided with excel sheets with  sheet1)contains nodes between which edges exist and their weights and sheet2) contains station name and node number by which it is represented. The example of the sheet in shown below:

  
-----------------------------------
Node1    |   Node2    |  Weights
---------|------------|------------
node1    |  node3     |    54
node143  |  node92    |    79
  .      |    .       |    .
  .      |    .       |    .
  .      |    .       |    .
  .      |    .       |    .
  

--------------------------
Node1    |   station name
---------|----------------
node1    |  station12
node245  |  station92
  .      |    .      
  .      |    .       
  .      |    .       
  .      |    .       
  
  
Problem statement : We have to write an algorithm to find the shortest and quickest path between any two stations and print all the stations name in that path.

Solution : I have used Djikstra algorithm to find the shortest path and for the quickest path i have used the same algorithm but have conaidered all the weights equals to 1.
