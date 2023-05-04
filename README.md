# Counting Transversal Matroids
This project finds and counts transversal matroids and is part of my Master's thesis (link not available yet) **Extensions of transversal matroids** for the [Master in Advanced Mathematics and Mathematical Engineering](https://mamme.masters.upc.edu/en) at UPC (Barcelona).

The code is written entirely in [SageMath](https://www.sagemath.org/), although most of the tools are Python native. The strategy that we follow is described in the referenced project.

## Format
File minimal_presentations.txt contains one minimal presentation of a transversal matroid in each line.
File maximal_presentations.txt contains one maximal presentation of a (distinct) transversal matroid in each line.

In these files, each line is of the form `n [{...}, {...}, ...]` where n is the size of the ground set and, between brackets, are the sets of the presentation.
Example: 5 [{1, 4, 5}, {2, 4, 5}, {3, 4}] 
