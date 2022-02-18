# Linked Lists and Big O

## Big O

---

### What is Big O

- Refers to the space and time efficency of an algorithm.
In order to analyze these, we should consider 4 key areas

1. Input size
2. Units of Meaasurment
3. Orders of Growth
4. Best Case, worst case, and average case.

### What is Input Size?

- Input size deals with the size of the input going into the algorithm.
- The Space and Time will usually increase with the increasing size of the input. an array of several elements would have a higher n value than a single integer. 

### What are Units of Measurment?

- In order to analyze run time we will consider three measurments of time

1. the time in millseconds from the start of a function execution until it ends
2. Number of operations that are executed.
3. The number of basic operations being run (the operation the is contributing the most to the total run time)

- In order to quanitfy the Memory space, we can consider the four sources of memeroy usage during the run time.

1. The amount of space required to hold the algorithm
2. The amount of space needed to hold the input data
3. amount of space needed for output data.
4. the amount of space required to hold working space during the calculation

### What are orders of growth?

- Orders of growth represent the incerease of run time and memory space.
- See charts and examples for details.


### Worst Case, Best Case and Average Case

- We can still think of the best and average cases even though bigO usually refers to the worst case scenario.
- see examples for each scenario.


### Review

- Big O = worst case analysis of an algorithim's efficiency
- Run time = time it takes to execute a algoritihm
- Memory space = the amount of storage required by an algorithm 
- Big theta = is the best case. 
- Big Omega is the average case.


## Linked Lists

---

### What is a linked list?

- A sequence of nodes that are connected/ linked together. 
- Each node references the next node in the link.
- Two types of lists, singly and double.
- Linear data structure akin to arrays, order matters.
- Memory that a linked list uses can be scattered about compared to an array that uses a single clump of storage. 7 in one place compared to 7 1's scattered about.
- dynamic data structures. A dynamic data structure can shrink and grow in memory. It doesnt need to set a mount of memory to be allocated in order to exist.



### Terminology

- Linked List = a data structure that contains nodes that links/points to the next list.
- Node = individual items that live in linked lists. Eaach node contains the data for each link.
- Head = the heaad reference of type node to the first node in the linked list.

### Big O

- The big O of time includes would be o(n). This is because we would have it iterate through the entire list of n nodes.

- The big O of space includes would o(1) because there is no additional space being allocated except for the input size of the linked list.


### Structure

- Head => node => node => node => Null
- a node is made up two parts, the data that it holds and the reference to the next node. 
- A NODE ONLY KNOWS ABPUT WHAT DATA IT HOLDS AND WHO ITS NEIGHBOR IS.


## Things I want to know more about

- Practice using linked lists.
- What are practical applications for using linked lists compared to other data structures?


---
## References and Citations

---

1. [Big O](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/big_oh.html)
2. [Linked Lists](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/singly_linked_list.html)
