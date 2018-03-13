# Matrix Conversion

This program is responsible for converting a matrix from one type of representation to another. It supports three types of the representation:
* Adjacency Matrix (MS)
* Adjacency List (LS)
* Incidence Matrix (MI)

The program recognizes a type of representation by a abbrevation mentioned in the parentheses. The matrix which we want to convert must be stored into the graph_in.txt

The format of writing them is showed below, each represantation represent an identical graph:
MS:
```
MS
0 1 0 0 1
1 0 1 1 1
0 1 0 1 0
0 1 1 0 1
1 1 0 1 0
```
LS:
```
LS
2 5
1 3 4 5
2 4
2 3 5
1 2 4
```
MI: (each connection is a row and column is a vertex)
```
MI
1 1 0 0 0
1 0 0 0 1
0 1 1 0 0
0 1 0 1 0
0 1 0 0 1
0 0 1 1 0
0 0 0 1 1
```
