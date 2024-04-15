# 0x1D. C - Binary trees

## Learning Objectives
### General
*What is a binary tree*
a binary tree is a tree data structure in which each node has at most two children, referred to as the left child and the right child. That is, it is a k-ary tree with k = 2. A recursive definition using set theory is that a binary tree is a tuple (L, S, R), where L and R are binary trees or the empty set and S is a singleton set containing the root
 
*What is the difference between a binary tree and a Binary Search Tree*  
The data in the Binary Search Trees (BST) is always stored in such a way that the values in the left subtree are always less than the values in the root node and the values in the right subtree are always greater than the values in the root node, i.e. left subtree < root node ≤ right subtree.


What is the possible gain in terms of time complexity compared to linked lists   
What are the depth, the height, the size of a binary tree  
What are the different traversal methods to go through a binary tree   
What is a complete, a full, a perfect, a balanced binary tree  


Binary search trees (BSTs) are a fundamental data structure in computer science with several key advantages as an abstract data type:

1. **Efficient Searching**: Binary search trees provide an efficient way to search for elements. With each comparison, the search space is halved, leading to an average time complexity of O(log n) for searching, where n is the number of nodes in the tree. This makes BSTs particularly useful in scenarios where quick retrieval of data is required.

2. **Ordered Data**: Binary search trees maintain their elements in sorted order. Each node in a BST holds a value that is greater than all values in its left subtree and less than all values in its right subtree. This property allows for operations like finding the minimum or maximum element in the tree, finding the successor or predecessor of a given element, and performing range queries efficiently.

3. **Insertion and Deletion**: Insertion and deletion operations in a BST are also efficient, with an average time complexity of O(log n). When inserting a new element, the tree can be traversed efficiently to find the appropriate location for the new node. Similarly, when deleting a node, the tree structure can be adjusted while maintaining the BST property.

4. **Flexible Data Structure**: Binary search trees can be used to implement various other data structures and algorithms efficiently. For example, they serve as the foundation for more advanced data structures like AVL trees and Red-Black trees, which provide additional balance properties to ensure optimal performance.

5. **Space Efficiency**: While BSTs maintain an ordered structure, they do not require additional storage for pointers beyond the data they store. This makes them relatively space-efficient compared to other data structures like linked lists, especially when considering scenarios with large datasets.

6. **Versatility**: BSTs can be used in a wide range of applications, including database systems, compiler design, network routing algorithms, and more. Their simplicity and efficiency make them a versatile choice for organizing and managing data in various computer science domains.

Overall, binary search trees are a powerful abstract data type due to their efficiency in searching, insertion, and deletion operations, as well as their ordered structure and versatility in applications.s

## Resources
### Read or watch:

+ [Binary tree](https://en.wikipedia.org/wiki/Binary_tree)
+ [Data Structure and Algorithms - Tree](https://www.tutorialspoint.com/data_structures_algorithms/tree_data_structure.htm)
+ [Tree Traversal](https://www.programiz.com/dsa/tree-traversal)
+ [Binary Search Tree](https://en.wikipedia.org/wiki/Binary_search_tree)
+ [Data structures: Binary Tree](https://www.youtube.com/watch?v=H5JubkIy_p8)
