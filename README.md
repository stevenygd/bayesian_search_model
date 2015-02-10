# bayesian_search_model

Introduction
====================

This project is an implementation of a Bayesian Search Model simulator based on Bayesian search theory. It contains both the algorithm for single searcher simulator and a multi searcher simulator.

Usage
====================

For Single Searcher Model, open the Mathematica notebook, evaluate the notebook. If you wish, configurate the following values:

objectData
---------------------
P(O) probability density distribution of whether the object is there), 

searcherData 
---------------------

P(D|O), which is the probability density function that the searcher will found the the target given the target is in the location). 

prec
---------------------

The smallest length of a unit area (will be partitioned into square)

rangeX,rangeY
---------------------

The range of X axis and Y axis. Both takes a list of {lowerbound, upperbound}
