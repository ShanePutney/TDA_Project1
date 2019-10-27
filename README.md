# Topological Data Analysis Project 1

## Introduction
It is apparent that within the field of Data Science, Topology is starting to be heavily used for data analysis. Our main focus for this project is classification. Our objective is to build a successful training model to predict letters from the Latin alphabet through the process of persistent homology. Before delving into our process for achiving our objective, let's first identify and define some key concepts that will be used. 


Now, the following is a brief summary of what will be done to hopefully achieve the objective of classification and prediction. A dataset will be created by reading 10x10 pixel images for each letter in the latin alphabet, which can be found in [Latin Alphabet](https://github.com/EnzoData/TDA_Project1/tree/master/Latin%20Alphabet/Latin%20alphabet.pdf), where the pixel values are 0 if there is no part of the letter and 1 otherwise.  Using the notebook Lower Star Image Filtrations from ripser.py, [Lower Star Image filtrations](https://ripser.scikit-tda.org/Lower%20Star%20Image%20Filtrations.html), the 0-Dimensional classes in each letter will be obtained in order to classify them through their Euclidean coordinates.

### Types of Scans
In the folder links below, there are examples of scanning methods used on the latin alphabet. These scanning methods are as follows: left to right, right to left,  top to bottom with each letter rotated 90 degrees, and bottom to top with each letter rotated 90 degrees. 
#### [Scanning (pdf)](https://github.com/EnzoData/TDA_Project1/tree/master/Scanning%20Methods)
#### [Scanning (ipynb)](https://github.com/EnzoData/TDA_Project1/tree/master/Scanning%20Examples)


## Algorithm
In the following folder link, the code used to classify letters can be found

#### [Algorithm](https://github.com/EnzoData/TDA_Project1/tree/master/Algorithm)


## Experiments
Testing 8 sparse letters - Enzo and Shane 

## Discussion 
why we went from 8 scans to 4 scans with 5 density scans
robustness 
From the algorithm produced and the results, we can see that classification was sucessful on the original 26 letter

## Criticism

## Literature Review

# Authors

* **Enzo Rodriguez** - [EnzoData](https://github.com/EnzoData)
* **Kevin Urure Cruz** - [kevinururecruz](https://github.com/kevinururecruz)
* **Sakshi Solanki** - [sakshisolanki](https://github.com/sakshisolanki)
* **Sri Nikhil Surapaneni** - [srinikhil96](https://github.com/srinikhil96)
* **Shane Putney** - [ShanePutney](https://github.com/ShanePutney)
* **Pratik** - [ppratik1995](https://github.com/ppratik1995)
