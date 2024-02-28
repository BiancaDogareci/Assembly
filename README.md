# Developed an x86 assembly project handling directed graphs, enabling input of adjacency lists to generate adjacency matrices. Extended functionality to calculate the number of paths of a specific given length between specified nodes, enhancing skills in low-level programming and graph theory.

## Project requirement 1:
- generate adjacency matrices

## Project requirement 2:
- calculate the number of paths of a specific given length between specified nodes

## Input:
1    // project requirement number
<br>
4    // number of nodes
<br>
2    // node 0 is adjacent to two nodes (nodes 1 and 2) 
<br>
2    // node 1 is adjacent to two nodes (nodes 2 and 3)
<br>
1    // node 2 is adjencent to one node (node 3)
<br>
0    // node 3 is adjencent to no nodes
<br>
1    // nodes which node 0
<br>
2    // is adjencent to
<br>
2    // nodes which node 1
<br>
3    // is adjencent to
<br>
3    // node which node 2 is adjencent to
<br>

## Output:
<br>
0 1 1 0
<br>
0 0 1 1
<br>
0 0 0 1
<br>
0 0 0 0


## Input:
<br>
2    // project requirement number
<br>
4    // number of nodes
<br>
2    // node 0 is adjacent to two nodes (nodes 1 and 2) 
<br>
2    // node 1 is adjacent to two nodes (nodes 2 and 3) 
<br>
1    // node 2 is adjacent to one nodes (node 3) 
<br>
0    // node 3 is adjencent to no nodes
<br>
1    // nodes which node 0
<br>
2    // is adjencent to
<br>
2    // nodes which node 1
<br>
3    // is adjencent to
<br>
3    // node which node 2 is adjencent to
<br>
2    // path length
<br>
0    // source node
<br>
3    // destination node
<br>


## Output:
<br>
2  // there are two paths of length 2 from node 0 to node 3 
