# Binary Search Trees


The search tree data structure supports each of the following dynamic set operations:
1. SEARCH
2. MINIMUM
3. MAXIMUM
4. PREDECESSOR
5. SUCCESSOR
6. INSERT
7. DELETE

Thus, a search tree can be used both as a dictionary and as a priority queue.

Basic operations on a Binary Search Tree take time proportional to the height of the tree. For a complete binary tree with n nodes, the operations run in $\Theta (log n)$ time, but for a chain of n nodes, the operations run in $\Theta (n)$ time, which is the worst case scenario. The expectation value of the height of a binary tree is $\log n$ and is thus it is more efficient.

## What is a Binary Search Tree?

A binary search tree is organized as a Binary Tree. You can represent such a tree with a linked data structure. In addition to a *key* and satellite data, each node object contains attributes *left, right* and *priori* that point to the left subchild, right subchild and and the parent respectively. If any of the parent or child values are missing, the corresponding attribute contains the value NIL. The tree itself has an attribute *root* that is pointing to the root node, or NIL if the tree is empty. The root node, given by $T.root$ is the only node in a tree whose parent is NIL. 

## Querying a Binary Search Tree

A binary search tree can support the following queries;
1. Minimum
2. Maximum
3. Successor
4. Predecessor
   
Along with the above operaaaaaaaaaaaaaaaaations, it can also support the operation of search. It can run the queries in $O(h)$ time, where $h$ is the height of the tree.

### Searching

To search for a node with a given key in a binary search tree, call the  Tree-Search Procedure, which works with a 