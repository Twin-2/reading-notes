# DS&A 1 8/20
[Back to menu](../README.md)

**You do not have to structly follow CF whiteboard example**

## Big O
a way to describve the complexity of the algorith without actually running it. 

Always the worst cae scenario

- time complexity 
- space complexity

Examples:
- O(1) constant - super efficient
- O(n) linear - grows over time
- O(log n) logarithmic - cuts in half over time

# Linked Lists
Linked list is the __concept__ that arrays are built off of.

list of nodes
- nodes are packages for info
- every node has at least 2 things: 
    - value
    - next (points to the next node)
- first node is the 'head'
- last node is 'tail' (next = null)

Traversal is fundimental, and all DS&A will have some traversal
- with LL's use a while loop testing if next is null, and then resetting current to current.next

## Questions
How acn you accieve log?

What is the head on a node?