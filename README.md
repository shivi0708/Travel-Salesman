# Travel-Salesman
the salesman has to travel to each village only once through the shortest path.

The problem to solve is that we have to visit each vertex exactly once with minimum edge cost in a graph.

the algorithm used is mentioned below and .cpp file is attached.


Consider city 1 (let say 0th node) as the starting and ending point. Since route is cyclic, we can consider any point as starting point.
Start traversing from the source to its adjacent nodes in dfs manner.
Calculate cost of every traversal and keep track of minimum cost and keep on updating the value of minimum cost stored value.
Return the permutation with minimum cost.
 
 
C++ Mini Project:
Group Members:
Naincy-9917102014(E1)
Sushant-9917102023(E1)
Shivangi-9917102025(E1)
