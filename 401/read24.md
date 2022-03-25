# Hash Tables

## Basics

---

- Hash = A hash is a result of some algortithm taking an incoming string and converting it to a value that can be used for either security or some other purpose. In the case of a hash table, it is used to determine an index of an array.
- Buckets = A bucket is what is contained in each index of the array of the hash table. Each index is a bucket.
- Collisions = A collision is what happens when more than one key gets hashed to the same location of the hastable.
- Data structures that use **key value** pairs.


### Why do we use them?

- To hold unique values
- Dictionary
- Library
- Since we are able to hash our key and determine the exact location where our value is stored, we can do a lookup in an O(1) time complexity. Ideal where lookups are required!
- Nearly every programming language has some sort of hash table data structure.
- Java uses `Maps`


### How would we write out own?

- We want to store a string, not a number. We want human readability. Computers do not know how to find an element with a string!
- In order to look up values by key, we need a way to convert keys into valid array indices. To do this we will use a `hash function`. 



### What makes a good hash function?

1. Fast (constant time)
2. Doesnt cluster outputs at specific indices, but distrbutes uniformly.
3. Deterministic (Same input yields the same output)


### Internal Methods

- Add()
- Find()
- Contains()
- GetHash()



## Resources/Citations

---

- [Hash Tables Codefellows Description](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-30/resources/Hashtables.html)
