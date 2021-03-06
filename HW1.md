## HW 1

![](https://github.com/Naturalenemy07/Algo/blob/main/undirgraph.jpg)
*Graph 1*

#### 1. What is the degree of node 7?
0 because node 7 isn't connected to any other node with an edge.
#### 2. If A is the adjacency matrix representation for the undirected graph, what is the value of A[2,6]
![](https://github.com/Naturalenemy07/Algo/blob/main/adjmtx.PNG)

*Adjacency matrix representing Graph 1*

A[2,6] is the integer in the second row and sixth column, which is 0

#### 3. What is the Python dictionary representation of the degree distribution  for Graph 1
The sum of the values needs to be equal to 1 since these are probabilities. The keys will be the degrees, and the values will be a probability of nodes with that degree.  There are 8 total nodes so if one node has a degree of 0, then the value for 0 for be 1/8 or 0.125.

```
degree_dist = {0: 0.125, 1: 0.125, 2: 0.25, 3: 0.375, 4: 0.125}
```

![](https://github.com/Naturalenemy07/Algo/blob/main/dirgraph.PNG)
                                                                                                                                                                             *Graph 2*

#### 4. How many nodes in Graph 2 have a in-degree of 2?
5, in degree is where the arrows are pointing torward a node

#### 5. If A is the adjacency matrix of Graph 2, what is the value of entry A[2,1]?

![](https://github.com/Naturalenemy07/Algo/blob/main/dirgraphmtx.PNG)

*Adjacency matrix representing Graph 2*

A[2,1] is the integer in the second row and first column, which is 0.

#### 6. How many nodes in Graph 2 have an out-degree of 2?
4, out degree is where the arrows are pointing away from a node

#### 7. What is the maximum possible degree of a node in an undirected graph *g* with length *n*?
A particular node can be connected by an edge to every other node *(n-1)* nodes.  

#### 8. What is the maximum possible number of edges in an undirected graph *g* with length *n*?
A node can be connected to a maximum or *n-1* nodes.  Multiplying this by every node (if we assume a directed graph) leads to *n(n-1)* edges.  Dividing by two converts this to the number of edges in an undirected graph since each directed node has a counter parallel partner.  Together they can count as a undirected edge.  Therefore the answer is *n(n-1)/2*
