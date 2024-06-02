# ModernClusteringMethods
This repository contains code for a TDA algorithm, which uses filtration functions to capture data properties.

# Algorithm comparison
In AlgorithmComparison.ipynb description and comparison of existing algorithms (ToMAto, HDBSCAN, Genie, DeBacl, Persistable) is provided.

# Developed algorithm
Code for the algorithm itself and its applications to generated datasets can be found in TDAclustering.ipynb file. \
Application pipeline is the following: \
![Screenshot](Shema.jpeg)
1) Pass data points as input
2) Create bifiltration from 2 filtration functions
3) Take slice or path of bifiltration
4) Extract single filtration function by traversing the slice
5) Build dendrogram to decide on threshold parameter
6) Extract flat clustering
