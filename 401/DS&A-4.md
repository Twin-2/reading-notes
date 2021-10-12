# Hash Talbes

## Data sctucture review

### LL

Traversal with a while loop resetting current to current.next

- truth table: a table of each itteration of the while loop

Travel with recursion: recall the function with current.next.

- Don't forget to set the end condition first.

WHY: carousel, lists, any time you need to re-use things in an order.

### Stack and Queue

Stack -> FILO

Queue -> FIFO

Traversal:

- pup or dequeue **if/while** peek() is true

WHY: When process order matters. When you want to process data so it won't be used again.

_**base case of recursion is when the loop should end**_

### Trees

BT -> two children

BST -> two children that are sorted large on right small on left

height is the number of edges (logical height -1)

Balanced? Left height vs right height.

Every node can be a sub tree with its branches and leaves.

WHY: Org chart, games (decisions for a quest that leads you to a specific path), file system.

Traverals:

- depth first: pre, in (sorted for a BST), post, order

- breadth first: level order, while loop with a queue.

### Hash Table

basically an array, but each key value pair of something you add get put into a new position in the array.

take the key as a string, convert it to a number, store at that number in the array.

**Can't** itterate the hash table

## Questions

What if they aren't strings? You can toString in javascript, others youhave to assume

How do you balance a tree

How do you build a tree from an array
