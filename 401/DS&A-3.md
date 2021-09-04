# Trees

## Cheat sheet

Traversal: depth vs breadth
- depth: recursion
    - Pre-order: root -> left -> right   **most common**
    - In-order: left -> root -> right
    - Post-order: left -> right -> root
- breadth: queue
    - go node by noed and add each child node left to right. 

Types of trees:
- binary: 2 children per node
- k-ary: k number of children per node

Binary search tree:
- **smaller** to the **left**
- **larger** to the **right**

Big O:
- O(n) almost all
- O(h) for binary search tree


# Lecture
All about hierarchical information

Real world trees: 
- file system
- the DOM is a tree

## Atributes of a tree
Levels are based on a 0 index count

## Traversal
Deptth first search
- walk through one sub tree before moving to any other sub trees. 

Breadth first
- uses a queue
- brute force method

'_functionName' is a naming convention for recusion function


## Questions

recursion? how does it go back up the tree?

How does recusion effect Big O?

is a Heap the same as a BST?

Why use one type of DFT over another?
