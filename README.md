# Network_Analysis_Jupyter_Notebook
#Enron Email Network

Analysis is based on Enron Email network data which is derived from http://www.cis.jhu.edu/~parky/Enron/. 
This contains a small subset of the large network.
This data was originally made public, and posted to the web, by the Federal Energy Regulatory Commission during its investigation.
Nodes of the network are email addresses and if an address i sent at least one email to address j, the graph contains an undirected edge 
from i to j. 

Notebook Goal- We are trying to parse the data into clusters and find out the central person in the network based on its clusters. 
Its an easy task but this model can be used for variety of use cases like Citation Network, Twitter network and so on. 


Further Analysis can be done based on the notebook result.

Process- 
1.Explore data
2.Compute the partition of the graph nodes which maximises the modularity by using the Louvain heuristices. (Cluster Partition)
3.Connected component to check whether the nodes are connected.
4.Betweeness Centrality for a particular cluster
5.Bfs_tree based on the most central node.
