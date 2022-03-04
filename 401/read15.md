# Trees


## Common Terminology Of Trees

---

- Node = A tree node is a component which contains a value and references to other nodes.
- Root - the node at the beginning of the tree, the peak of the mountain. 
- K = A number that defines how many children a parent node can have in a k-ary tree.
- Left = A reference to a one child node in a binary tree.
- Right =  A reference to the other child node in a bindary tree.
- Edge = The edge in a tree is the link between a parent and a child node.
- Lead = A node with no children. 
- Height = The height of a tree is the number of edges from the root to the furthest leaf.


### Other characteristics

- Lists are linear, **trees** are linear. Many different paths you can take.

### Different applications of trees

- HTML DOM 
- React
- Artificial Intelligence
- Folder Operating System


### Different Kinds of Trees?

Below are some examples. There are alot.

- K-ary Tree
- Heaps
- Binary Search Trees.
- Binary trees.


#### Binary Search Trees

- Have at most 2 children
- Kept in an order
- Used to store data that can be compared. 
- Every node to left is always **less** than the parent node.
- Every node to right is always **greater** than the parent node.



### Tree Traversal 

How do we visit every node ***one*** time?

#### Four common examples of traversal

- Breadth First => breadth of the tree (horizontal traverse)
- Depth First => depth of the tree (vertically traverse)


##### Breadth First (Iterativly)

- Create a queue and a variable to store the values of nodes visited.
- Place the root node in the queue.
- Loop as long as there is anything in the queue.
- Dequeue a node from the queue and push the value of the node into the variable that stores the nodes.
- If there is a left property on the node dqueued - add it into the queue.
- If there is a right property on the node dequeued - add it into the queue.
- Return the variable that stores the values of each node. 



## Resources/Citations
---

- [Trees](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-15/resources/Trees.html)
