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
The sum of the values needs to be equal to 1 since these are probabilities.  There are 9 total edges and since it is an undirected graph, 9x2 = 18 total connections.  

'''
dict = {0:(3/18), 1:(3/18), 2:(3/18), 3:(2/18), 4:(2/18), 5:(1/18), 6:(4/18), 7:0}
    
    = {0:0.167, 1:0.167, 2:0.167, 3:0.111, 4:0.111 , 5:0.056, 6:0.222, 7:0}
'''
